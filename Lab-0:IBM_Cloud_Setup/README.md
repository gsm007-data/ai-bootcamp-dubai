
# Lab:0 - IBM Cloud Setup

🎯 Objective
This pre-work lab is intended to set up the foundational IBM Cloud credentials required for the bootcamp. You’ll generate and securely store the following mandatory credentials:

- API Key

- Project ID

- Space ID

These values are essential for running various hands-on exercises and labs throughout the bootcamp. Follow the below steps to create the above. 

## Step-1: Create IBM Cloud account (if not created) 

If you've not created your IBM cloud account, please refer the link and create your IBM account with your personal/business email id. 

[Create IBM Cloud account](https://www.ibm.com/account/reg/us-en/signup?formid=urx-19776)

## Step-2: Go to our email ID and join the IBM cloud account. 

![Banner](images/img001.png)

## Step-3: After login, this is how your IBM cloud account looks like. 

![Banner](images/img002.png)

## Step-4: Create API Key 

1. Go to - "Manage" > "Access (IAM)"

![Banner](images/img003.png)

2. Click on - "API keys" > "Create"

![Banner](images/img004.png)

3. Give a "Name" and "Description" to the API key and click on "Create"

![Banner](images/img005.png)

4. API key is successfully created. **You copy it and save it or download it.**

![Banner](images/img006.png)

## Step-5: Create Project in watsonx.ai 

1. Click on the **Hamburger Menu**

![Banner](images/img007.png)

2. Click on "Resource list" 

![Banner](images/img008.png)

3. Under "AI / Machine learning", you can see 4 options. Click on the one with "watsonx.ai Runtime" 

![Banner](images/img009.png)

4. Under "Launch in", click on **"IBM watsonx"**

![Banner](images/img010.png)

5. Now you'll be navigated to watsonx sudio. It's time to login with your email ID, which has IBM cloud access (from Step-1). 

![Banner](images/img011.png)

6. Once logged in, click on the "Hamburger menu" in the top left corner 

![Banner](images/img012.png)

7. Click on "View all projects"

![Banner](images/img013.png)

8. Click on "New project"

![Banner](images/img014.png)

9. Give a "Name", "Description (Optional)", "Tags (Optional)", and then go to define storage. 

![Banner](images/img015.png)

10. Select a storage, and then click on "Create". Now your project is created. 

![Banner](images/img016.png)

11. Click on "Manage" > "Servics and integrations" > "Associate service". (This step is to associate machine learning services to the project)

![Banner](images/img017.png)

12. Check mark on the "watsonx.ai Runtime" service. 

![Banner](images/img018.png)

13. Now you can see wml (Watsonx Machine Learning) service is associated with the project. 

![Banner](images/img019.png)

14. Go to "Manage" > "General". Now you can see your "Project ID". **Copy it and save it**. 

![Banner](images/img020.png)


## Step-6: Create Deployment space watsonx.ai 

1. Click on the "Hamburge menu" (Top left corner). 

![Banner](images/img021.png)

2. Click on "View all deployment spaces" 

![Banner](images/img022.png)

3. Click on "New deployment space" 

![Banner](images/img023.png)

4. Now you mention a name to your deployment space. 

![Banner](images/img024.png)

5. Select watsonx.ai Runtime (Optional). 

![Banner](images/img025.png)

6. Now it'll take a while to create the deployment space. 

![Banner](images/img026.png)

7. Now your deployment space is created. 

![Banner](images/img027.png)

8. Click on "Manage" > "General" and then copy "SPace GUID". **Copy it and save it in your note". 

![Banner](images/img028.png)


## 🔔 Note - By the end of this exercise, ensure you have securely saved the following credentials:
1. API Key
2. Project ID
3. Space ID

These credentials will be required at multiple stages throughout this bootcamp, so keep them handy for future use.






