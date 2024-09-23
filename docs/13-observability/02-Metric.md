--- 
title: "Metric"
---

# Metric 
<span className="mediumFont">
  The metric indicates the application's performance trends over time.
  </span>

<!-- <span className="smallFont"> -->
There are three key metrics :

 **1. Request Rate metric :**
    The request rate metric quantifies the frequency of incoming requests to a server or application over a specified time period, typically expressed in requests per second (RPS)

   **Use cases**
     1. Traffic Pattern Analysis
     2. Resource Utilization Assessment
     3. Bottleneck Detection
     4. Capacity Planning
     5. Performance Optimization
     6. Alerting and Monitoring

  **2. Error Rate metric :**
  The error rate metric measures the frequency of errors in an application as a percentage of total requests, indicating reliability and performance. A high error rate signals potential issues that need addressing to enhance user experience.
    
   **Use cases**
     1. Application Health Monitoring
     2. Issue Identification
     3. Alerting Mechanisms

  **3. Duration :**
  Duration is a metric that indicates the time taken between a request and its corresponding response, reflecting the application's performance and responsiveness.
     
   **Use cases**
     1. Performance Monitoring
     2. User Experience Improvement

##  Accessing metric tab 
  To view the metric, follow these steps:

1. Select the **Observability** option from the sidebar.
2. Choose the **metric** tab from the sub-options under Observability.
3. You can now view the request rate, error rate, and duration graphs for all workspaces, as all workspaces are selected by default.

     ![create_app](/assets/observability/observabilitymetric.png)

  
    ### Filter metrics by workspace 
     On the right side of the metrics page, there’s a dropdown menu for selecting a workspace. You can choose between "All Workspaces" or a specific one.

       ![create_app](/assets/observability/metricWorkspaceFilter.png)


    ### Filter metric by Environment (Test/Stage/Production)
     Next to the workspace filter, you’ll find three options to select the environment. You can choose the specific environment for which you want to view the metrics.
   
       ![create_app](/assets/observability/merticEnvFilter.png)

    ### Filter metric by Time range 
     You can view metrics for a specific time frame by selecting either absolute time or relative time.

       ![create_app](/assets/observability/timeFilter.png)
    
    ### Specific application metric 
     Scrolling down on the same page, you’ll find a section titled "Application Status," which displays all applications along with brief metric details for the selected workspace. 
     [(Let’s take a closer look at each application metric.)](http://localhost:3000/docs/observability/appMetric)

     ![create_app](/assets/observability/metricAppStatus.png)

  <!-- </span> -->