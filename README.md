# Grafana-sso
---
## prerequisite:
- SSL Cert Required
- Genericoauth
---
## Step-1:
```
Create app registration from azure portal follow the same steps as zabbix sso doc.
```
---
## Step-2:
```
Create 3 groups for grafana role mapping ,ie: Admin, Editor, viewers.
```
---
## Step-3:
```
Add users in those groups.
```
---
## Step-4:
```
Go to token configuration from App registartion, add a group claim to the token if its not there.
```
---
## Step-5:
```
Make sure you change the SSO conf in .ini And Gui Authentication as well
```

