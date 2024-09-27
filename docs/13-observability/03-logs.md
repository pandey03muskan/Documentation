--- 
title: "Logs"
---

# Logs 

<span className="mediumFont">
Learn how to search and filter your logs based on both absolute time ranges and relative time frames.
</span>
<div className="mediumMarginTop">
Logs allow you to view and filter your runtime logs without the need for any third-party integrations. You can search logs based on the following attributes: environment, application name, and workspace name.
</div>

### View Logs 

<!-- <span className="smallFont"> -->
To view logs, follow these steps:

1. Select the Observability option from the sidebar.
2. Choose the Logs tab from the sub-options under Observability.
3. Here, you can search by attributes and filter based on relative time frames.

       ![create_app](/assets/observability/logs.png)

<!-- </span> -->


### Search for Logs 
<!-- <span className="smallFont"> -->
You can search the observability logs using both keywords and attributes. For example:

**Keyword Searches:** Utilize keywords such as 200, 201, 404, or warning to filter relevant logs.

**Attribute Searches:** Refine your search by specifying attributes, such as:

workspace_name=`<workspace-name>`
env=`<test/prod/stg>`
app_name=`<app-name>`

This dual approach enables more precise and effective log analysis.
The Logs section also stores the log search history for future reference.
<!-- </span> -->

### Filter Logs 
You can filter the search results based on relative time frames.

