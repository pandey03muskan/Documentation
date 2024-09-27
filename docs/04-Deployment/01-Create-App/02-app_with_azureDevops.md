--- 
title: "App with azureDevops"
---

# Deployments

## Seamless app deployments

- ## Create Application from Source Code (Azure Devops)
 
  Your journey to seamless deployments starts here. Just a few steps!

  **1**. To create a new application deployment, click on the **CREATE** right on your Dashboard.
 
       ![create_app](/assets/create_app/azure_create_button.png)

  **2.** Name your application, select workspace and choose your codebase.

       ![create_app](/assets/create_app/Select_azureCodeBase.png)

  **3.** To link your codebase, you’ll need to install initializ on your Azure Devops. Seems hard?
No, it’s not. Just **Click! Click! Click!**.

   -   Click on the “Edit Your AzureDevOps Permissions” link.

               ![create_app](/assets/create_app/azure-devops.png)

    -  Choose initializApp to Install and Configure.

    -  Grant access to Organization and projects as per your choice. Don’t worry, it’s completely safe.

    -  Authorize initializ with Azure Devops.
       
                ![create_app](/assets/create_app/azure_account.png)

     After this you’ll be redirected back to initializ.ai where you can select an organization ,project and repository for your application .

    **4.** Select organization, project and repository for your app deployment.

      ![create_app](/assets/create_app/azure-devops-org.png)

    **5.** Done? Click next! Let’s choose Configurations for our deployment.

- ## Configure

   **1.** Select Environment and add Environment Variables appropriate to your application. You can also add .env, .yml or .json file.

      ![create_app](/assets/create_app/azure_env.png)

   **2.** Select Resource Settings. Select appropriate Port, Path (a combination of console address and domain entered by you), Instance size and number of instances.

      ![create_app](/assets/create_app/configure_azure.png)

**Tip**💡
**_You can also enable vertical auto-scaling. Vertical Auto-Scaling allows the App to use resources beyond the request when needed._**

- ## Review

   Once you have selected codebase and resources, you can Review and Deploy your App. If you feel like editing something, just hit BACK.

