## Testing tokenrouter api with Kimi K3 free model inside google app script

#### Step 1<br>
goto <a href='https://script.google.com/home'>google app script home</a> to create a new project<br>
<br>
#### Step 2<br>
find the <a href='https://raw.githubusercontent.com/WingsMaker/kimi-k3-demo/refs/heads/main/google_script.txt '>google_script.txt</a> in this github<br>
copy-paste the content onto the google script project<br>
<br>
#### Step 3
goto www.tokenrouter.com to register free account, get a free api key<br>
paste the api key value onto the line 14 <br>
    const apiKey = "......";<br>
<br>
### Step 4<br>
goto the bottom of the script where function testKimiK3 is, change the code:<br>
  const prompt = "...put in your own prompts";<br>
<br>
### Step 5<br>
at the top of the Apps Script editor, find the dropdown list between "Debug" and "Execution log".<br>
Select "testKimiK3" and click the "Run" option to test run<br>
<br>
<img width="920" height="132" alt="image" src="https://github.com/user-attachments/assets/98032017-45bb-49b4-ad76-a0bc278492c9" />
<br>
Click on the "Execution log", you will see the results of the test run<br>
<a href='https://raw.githubusercontent.com/WingsMaker/kimi-k3-demo/refs/heads/main/execution_log.txt'>Example execution log</a>
<br>
For python version, see kimi.py
