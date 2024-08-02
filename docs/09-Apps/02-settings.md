---
sidebar_position: 02
title: "App settings"
description: ""
---

# Settings


  - ### App settings

    In the "App Settings" section, you will find the current HTTP port, HTTP path, app instance, minimum and maximum number of instances. Additionally, you will have the option to enable or disable Auto-Scaling during the app deployment process.

    <!-- image -->

    #### Update App settings

     Follow these steps-

     - To update the "App Settings" click on "Edit".
        <!-- image -->
     - Make the necessary changes and click "Save".
        <!-- image -->

     After clicking "Save", the changes will be successfully updated.

      > You can update the "App Settings" in two scenarios - 
      > 1. Your application has been successfully deployed.
      > 2. The application status is "Failed".


  - ### Environment Variables

    You can store your environment variables based on the environment, meaning that for the same key, you can have different values for different environments (Production, Testing, Staging). You can also use .env, .yml, or .json files to import bulk of environment variables.

    Additionally, you will be able to select the type of key: secret, secretRef, or Env.

       <!-- image -->

      > **secretRef** - The 'secret reference' type of key is selected when you need to refer to a secret from the security management [(Learn More)](http://localhost:3000/docs/SecurityManagement/securitymanagementdasgboard)




    #### Update the Environment Variables

     Follow these steps-

     - To update the "Environment Variables", click on "Edit".
        <!-- image -->
     - Make the necessary changes and click 'Save.' For a single key, you can set different values for Testing, Staging, and Production, or you can set the same values for all environments.
        <!-- image -->

     After clicking "Save", the changes will be successfully updated.

     >You can update the "Environment Variables" in two scenarios-
     >1. Your application has been successfully deployed.
     >2. The application status is "Failed".

  - ### Setting custom domain

      Once your application is successfully deployed, you will receive a URL for each environment: Production, Staging, and Testing. The platform also offers the option to use your own custom domain.
 
       > **Note** - You can set a custom domain only after the application has been successfully deployed.

    #### How to set custom Domain
        
    - In the application's settings tab, you will find a "Domain" section with an "Edit" option. 
          <!-- image -->
    - Enter your custom domain for each environment: Production, Testing, and Staging.
      <!-- image -->
    - Now click "Save", and you are good to go.



  - ### Delete the App

      In the Settings section, at the bottom of the page, you will find an option labeled "Destroy." Click on "Destroy" to proceed with deleting your application along.
      
       <!-- image -->

