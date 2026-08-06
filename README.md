## this is a demo on how to test tokenrouter api with Kimi K3 free model inside google app script

#### Step 1
goto script.google.com/home
create a new project

#### Step 2
find the google_script.txt in this github 
copy-paste the content onto the google script project

#### Step 3
goto www.tokenrouter.com to register free account, get a free api key
paste the api key value onto the line 14 
    const apiKey = "......";

### Step 4
goto the bottom of the script where function testKimiK3 is, change the code:
  const prompt = "...put in your own prompts";

### Step 5
at the top of the Apps Script editor, find the dropdown list between "Debug" and "Execution log".
Select "testKimiK3" and click the "Run" option to test run
