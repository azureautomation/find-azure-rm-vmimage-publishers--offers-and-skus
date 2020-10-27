Find Azure RM VMImage Publishers, Offers and Skus.
==================================================

            

When you deploy a Virtual Machine Image, you need to know the 
Size of the Virtual Machine, this script can help to get the Sizes in your region:


[https://gallery.technet.microsoft.com/scriptcenter/Find-Azure-RM-Virtual-8ee175d5?redir=0](https://gallery.technet.microsoft.com/scriptcenter/Find-Azure-RM-Virtual-8ee175d5?redir=0)


 


You also need to know the following information:


    **Version                   PublisherName            Offer                Skus
           **
    2016.127.20170406 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170421 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170510 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170630 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170712 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170822 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20170918 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20171017 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20171116 MicrosoftWindowsServer WindowsServer 2016-Datacenter
    2016.127.20171217 MicrosoftWindowsServer WindowsServer 2016-Datacenter


    **Version            PublisherName Offer Skus**
    7.3.20161104   RedHat                RHEL  7.3

    7.3.20170201   RedHat                RHEL  7.3

    7.3.20170223   RedHat                RHEL  7.3

    7.3.2017032021 RedHat              RHEL  7.3

    7.3.2017042521 RedHat              RHEL  7.3

    7.3.2017051117 RedHat              RHEL  7.3

    7.3.2017052619 RedHat              RHEL  7.3

    7.3.2017053019 RedHat              RHEL  7.3

    7.3.2017062722 RedHat              RHEL  7.3

    7.3.2017071923 RedHat              RHEL  7.3

    7.3.2017081103 RedHat              RHEL  7.3

    7.3.2017081120 RedHat              RHEL  7.3

    7.3.2017090105 RedHat              RHEL  7.3

    7.3.2017090723 RedHat              RHEL  7.3


 


There are hundreds of publishers to select from and each of those publishers has many offers and Skus.


This function helps to find the info that you need to deploy the image that you are looking for.


 


**Find-AzureRMPublisherImageOffer -Location EASTUS2**


** **![Image](https://github.com/azureautomation/find-azure-rm-vmimage-publishers,-offers-and-skus./raw/master/publisher.png)


![Image](https://github.com/azureautomation/find-azure-rm-vmimage-publishers,-offers-and-skus./raw/master/okay.png)** *** *


**Next it will prompt for the Offer that you need.**


** **


![Image](https://github.com/azureautomation/find-azure-rm-vmimage-publishers,-offers-and-skus./raw/master/offer.png)


**Then the SKU**


![Image](https://github.com/azureautomation/find-azure-rm-vmimage-publishers,-offers-and-skus./raw/master/sku.png)** *** *


**Finally it outputs the Info in a Summary Table.**


![Image](https://github.com/azureautomation/find-azure-rm-vmimage-publishers,-offers-and-skus./raw/master/image.png)** *** *


 


Here is a sample Script to Create a Virtual Machine Using PowerShell


[https://gallery.technet.microsoft.com/scriptcenter/Deploy-a-new-Virtual-75cd3230?redir=0](https://gallery.technet.microsoft.com/scriptcenter/Deploy-a-new-Virtual-75cd3230?redir=0)


[](https://gallery.technet.microsoft.com/scriptcenter/Deploy-a-new-Virtual-75cd3230?redir=0)

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
