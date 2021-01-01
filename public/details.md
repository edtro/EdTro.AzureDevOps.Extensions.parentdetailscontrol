**Parent Details Control** enables every user to review the details of the parent workitem, directly within the form of the child workitem

> LICENSE: This is a free showcase project to show the possibilities of creating extensions for Azure DevOps Server/Services and the Formula Design System (ref: https://developer.microsoft.com/en-us/azure-devops/). It is provided by **Inetum-Realdolmen** 'as-is' under the general MIT license issued within the support page (on GitHub). So feel free to install it, try it out and use it in any of your organizations. But do this at your own risk, no guarantees and/or no warrentees of any kind are provided.

## Introduction
One of the nicest features of TFS / Azure DevOps Services is that you can setup multiple levels of workitems. But when for example you want to split up the User Story into several tasks for different activities like Design, Development, Test and Deployment... it is a bit tiresome to go back to the parent User Story each time, to see what has to be done.

This custom control will display detail information, like the Description and Acceptance Criteria of the parent, within the child workitem.


## How does it work?
Navigate to your work item form customization page and add a Parent Details custom control.

Setup the following custom control properties:
- Set the 'FieldName' property to the 'Description' field. When something is filled in, the control will be collapsed.
- Set the 'ContentFields' property with semi colon seperated values of the fields that have to be displayed, like 'System.Description;Microsoft.VSTS.Common.AcceptanceCriteria'

 
## Known limitations
* This extension is currently only available on Azure DevOps Services and Azure DevOps Server (demands the API version 5.0 at least; so it works on-line and on the on-premises versions 2019 and 2020);
* Be aware: this extension is created and supported for "on-line" first (like many other extensions). For "on-premises" instances there is limited support;
* Only tested and validated on Chrome, FireFox and Edge (the new Chronium based version) for a regular non-touch device;
* Only tested and validated on Safari (IPhone) for a touch device.

(please review: https://github.com/edtro/EdTro.AzureDevOps.Extensions.parentdetailscontrol/issues)


## Feedback
Please feel free to leave a behind your feedback within the Q & A section. We love to hear from you.


## Changelog

| Version | Description |
|---------|-------------| 
| 0.21001 | Initial version.|

If this project inspires you and/or you have specific requirements that are not not implemented within the standard and/or this project, please feel free to contact us, so we can see how we can help.

Created by **Inetum-Realdolmen**, please contact us at: https://www.realdolmen.com/en/solution/microsoft-application-lifecycle-management
<br/>
![screenshot](img/inetum-realdolmen-becomes.png)
<br/>

