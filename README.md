Azure Analysis Services - Scale and Pause or Resume using scheduled autoscaling
===============================================================================

            

This Azure Automation runbook enables vertically scaling or pausing of an Azure Analysis Services server according to a schedule. Autoscaling based on a schedule allows you to scale your solution according to predictable resource demand. For example you
 could require a high capacity (e.g. S1) on monday during peak hours, while the rest of the week the traffic is decreased allowing you to scale down (e.g. S0). Outside business hours and during weekends you could then pause the server so no charges will be
 applied. This runbook can be scheduled to run hourly. The code checks the scalingSchedule parameter to decide if scaling needs to be executed, or if the server is in the desired state already and no work needs to be done. The script is Timezone aware.


jorgklein.com for more information.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
