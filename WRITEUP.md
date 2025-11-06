# Write-up

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For a VM solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
  - Higher cost as it considers VM compinter, OS license, storage, networking. Many resources = more $$$
  - Manual or automated scalability means added complexity and oh did I mention more money?
  - Provides higher availability at the cost of higher complexity and oh yea monies.
  - More fine grained customization which expands the options for workflow and DevOps.

*For an App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
  - Lower cost for typecal web app. The justification for this type of app is that its a simpler webpage.
  - Built in scalability which means we can focus on the code which is already a complex enough task ya
  - Includes multi instance support and HA however, this would mean more mula and we are on a budget here since Udacity will not give us a lab with the proper rights to create certain resources.
  - Limited control and customization but still more than enough for the purposes of this project.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

With the reasons mentioned above, plus the rubric already highlights this as the easier path, the winner is: App Service.
