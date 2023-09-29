## Github Actions : Starter workflows

### Notifications Google Chat

#### Google Space webhook
1. Create a Google Space dedicated to the notifications
2. In the Google Space settings, create a new webhook
3. Copy the link of the webhook

#### Github Actions secret
4. Go to the "Settings" tab of your Github repository
5. Go to "Secrets and variable" > "Actions"
6. Add a New Repository Secret
7. In the name, put "WEBHOOK" (without the quotes)
8. In the secret, paste the link of your Google Space webhook (cf. 3)

#### Add a new Github Actions workflow 
9. Go to the "Actions" tab of your Github repository
10. Under the "By kiloutou" category, select the starter workflow that you want and click on the "Configure" button
11. Commit the changes and you're done !
