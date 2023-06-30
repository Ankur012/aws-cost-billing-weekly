# Get AWS Resources Weekly Bills on Slack in Table Format

### This Python script will get a two-week(last to last week and last week) aws resource cost and show it in table format which helps to understand how much the cost of aws resource is weekly.
#### First thing first, Install Python libraries, need following. some of the pre-install in your system.
- json
- datetime
- calendar
- slack_sdk
- boto3
- prettytable

```
pip3 install slack_sdk boto3 prettytable
```


#### prerequisite
* you must have a Slack bot API token with file upload permissions.
* you need a Slack channel ID.
* AWS user with required permission(for the beginner/test you can use admin policy.)
* Some Python, JSON, and  dictionary understanding.

#### In my case, running the script from the laptop, you can run from AWS lambda or CICD pipeline based on your case.
## Note: my python version:- 3.10.9 


```
python3  get-aws-weekly-report.py
```

#### report
<img width="1406" alt="Slack_Notifcation" src="https://github.com/Ankur012/aws-cost-billing-weekly/assets/12594345/0dc019d7-a4a4-48dd-ab8e-0a35ec02d144">

