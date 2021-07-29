# Jenkins CI/CD
![img.png](img.png)

## Creating a new job in Jenkins
- Click on `New Item`
- Enter appropriate item name and choose `freestyle project`
- Add description about the job
- Click `Discard old builds` and put 3 in `Max # of builds to keep`
- Click `Add build step` and `Execute shell` 
- Write in necessary code, apply and save
- Build job to see if it is successful
- If you have another job to execute after this choose `add post build action`
- Choose `build other projects` and add the project to build

## CI/CD
- On the relevant GitHub repo click on settings -> webhook and create a webhook
- Name the webhook and the URL is `http://JENKINSIP/github-webhook/` make sure deploy key is read/write
- Create a new job 