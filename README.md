Stop Azure VMs in a subscription using Python from Azure Automation
===================================================================

            

 


Stops Azure resource manager virtual machines in a subscription.

This Azure Automation runbook runs on Azure to stop (deallocate) Azure vms in a subscription.
If no arguments are specified, then all VMs that are currently started are stopped.
If a resource group is specified, then all VMs in the resource group are stopped.
If a resource group and VM are specified, then that specific VM is stopped.

Args:
    groupname (-g) - Resource group name.
    vmname (-v) - virtual machine name

    Stops the virtual machines
    Example 1:
            stop_azure_vm.py -g <resourcegroupname> -v <vmname>
            stop_azure_vm.py -g <resourcegroupname>
            stop_azure_vm.py


** *** *


 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
