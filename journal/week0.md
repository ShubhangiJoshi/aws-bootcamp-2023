# Week 0 — Billing and Architecture

# Required Homework
1)  GIT - created new repositiry 
2)  GIT - Used template shared by AB
3)  GIT - Installed chrome extension for gitpod
4)  GIT - setup GitPOD as directed on gitpod link/ week0 setup vid
5)  GIT-  Main branch and week 0 barch created. 
6)  GIT - did not try fork or anything to get AB's other workspace.
7)  <>
8)  AWS - Root account and IAM user created
9)  AWS - Cloud shell used. tried "aws sts get-caller-identity 
10) AWS - Region selected -> ap-south-1
11) AWS - AWS CLI setup on main branch and sub branch
12) AWS - as per Ab's gguidance, bills, budgets, alarms are setup using json and commands. 
13)  <addtional space>
14)  <>
15)  GIT - Main branch is updated for basic changes
16)  GIT - Few details such as budget and biling alarm is committed to week 0 branch only
17)  GIT - Environmental vaibales are stored through aws CLI
18)  GIT - Sensitive data such as secret key is removed and committed again.
19)  Lucid - Created Logical structure of crudder application


###Errors faced ( planning to maintain error log )###
1) Post IAM user created, used the link and though password was noted on scrap pad , faced troubled logged in. so removed IAM user and created new one.
2)
3) An error occurred (InvalidClientTokenId) when calling the GetCallerIdentity operation: The security token included in the request is invalid. -> Whenever I restart my work after break or there is a discontinued session, I get this error . The only solution I got is resetting 2 environment variables as export AWS_ACCESS_KEY_ID='your access key id here';
    export AWS_SECRET_KEY='your secret key here'

4) Unknown options: <Account id> -> Made mistake while typing budget.json. --account-id = $AWS_ACCOUNT_ID \ >> added '=' unintentionaly. 
5) git opn install - As per AB's advice, was trying to see bash but , dint know how to stup running open command. so killed the terminal forcefully. finally understood ctrl+ c ( mac) would help me kill the task .
  
  
##  Work to be done ##
1) GIT repo clean up. Main branch is not updated with live data. AB directed to update main branch.
2) Encryption of sensitive data keep repo public
3) Lucid charts for - 1) Context diagram 2) security  architecture diagram 3) data architecture
4) <AOB>
  
  
  
  
