--- 
title: "Forwarding"
---

<span className="mediumFont">
Learn how to create a sink for efficiently forwarding data and logs from your application.
</span>

<!-- <span className="smallFont"> -->
In this section, you will learn how to set up a sink to effectively forward data and logs from your application, ensuring streamlined data collection and analysis.

In order to create sink, follow these steps :

**Step 01 :** Create Account on splunk cloud platform.[(click here)](https://www.splunk.com/en_us/download.html) (For now only splunk option is available on platform).

**Step 02 :** After verifying and logging into your account, create a token.
       1. Go to Settings and click on "Data Input".
      
           ![create_app](/assets/observability/splunkToken.png)
    
       2. Now, fill in the necessary details and click on "Next".

           ![create_app](/assets/observability/forwardingTokenName.png)

       3. Choose the index and click on "Next." After that, you will see a preview screen. Review the information and submit.


          _Index : The Splunk platform stores incoming data as events in the selected index._


       4. Now you will see a "Token Value." Copy the token value and the URL.

           URL format should be - <span className="importantText"> https://`[hostname]`:`[port]`/services/collector</span>
       

            ![create_app](/assets/observability/ForwardingToken.png)

**Step 03 :** Go to the "Forwarding" section under "Observability" and click on "Create Log Sink."
                   ![create_sink](/assets/observability/createSink.png)

**Step 04 :** Fill in the necessary details and click on "Create."

                   ![create_sink](/assets/observability/SinkForm.png)

**Step 05 :** Your sink has been successfully created. Now, if any activity or event occurs in the applications deployed on the "Initializ.ai" platform, you will be able to see it in your Splunk Cloud account. You can now perform real-time analytics, utilize advanced search options, and create customizable visualizations, enhancing your monitoring capabilities.


<!-- </span> -->