![](/images/ahlsbanner.png)
<h1>A-HLS Create Event Workflow - Documentation</h1>

A quick OmniScript that can be placed on various object record pages to quickly create events that are related to the current record.

<h2>Overview</h2>

Events are a powerful tool for keeping on top of customer relationships and closing deals. By using event records, you and your sales teams can keep better track of your calendars. This helper is a process which allows users to create such events quickly. 

<h2>Use Case Scenario</h2>

As a user of the application I need to be able to create an event quickly. 

<h2>Business Value and Benefits</h2>

* Reduction in the time and cost pertaining to the event creation. 
* Increased efficiency in managing multiple events. 


<h2>Package Includes</h2>


*OmniScript (1)*

* createevent

*DataRaptor (6)*

* ContactCenterContectObjectIDExtract
* ContactCenterCreateEvent


<h2>Configuration Requirements</h2>

<h3>Installation Instructions:</h3>

1. Follow the download steps presented on the Accelerate HLS website for this Accelerator. 
    1. Alternatively, you may download the Data Pack folder in the following GitHub repository: https://github.com/HLS-Accelerate/contact-center-event

1. Then, complete the following steps to import them into your Salesforce org.
    1. To Import, in your destination Salesforce org, Click on *App Launcher* → Search for '*OmniStudio DataPacks*' and click on it.
    2. Click on '*Installed*' and on the right side click on '*Import from*'.
    3. Select '*From File*' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '*Install*'.
    4. When prompted to Activate the OmniScript, choose *Not Now*.

<h3>Post-Install Configuration Steps:</h3>

1. Click on *App Launcher* → Search for “OmniScripts”
    1. Navigate to the recently installed OmniScript in the list view
    2. Click on the dropdown at the right of the OmniScript and select *Activate*.
    3. For more information regarding activating Omniscripts, please see this article: https://help.salesforce.com/s/articleView?id=sf.os_activating_omniscripts.htm&type=5
2. Add the installed OmniScript to the lightning page layout of your choosing. 
    1. Refer to this article for more information regarding adding OmniScripts to a Lightning or Experience page: https://help.salesforce.com/s/articleView?id=sf.os_add_a_standard_omniscript_component_to_a_lighting_page_20263.htm&type=5
3. You will need to supply your own Google Maps API key to use the Google API in the Address field.  
![](/images/APIKey1.png)
    2. If you wish not to use the Google Maps API or do not have an API Key you can simply turn it off by deselecting the “Enable Google Maps Autocomplete” checkbox.
![](/images/APIKey2.png)


<h2>Assumptions</h2>

* A customer has licenses for Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.
* A customer is assuming Salesforce Lightning Experience — not Classic.
* Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.
* The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved. 


<h2>Revision History</h2>

* Initial Release - June 21, 2022 
* Updated documentation - September 26, 2022

