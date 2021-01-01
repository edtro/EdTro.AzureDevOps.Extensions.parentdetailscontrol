
> NOTE: at this moment, no detailed documentation exist on how to configure this extenions. 

## How does it work?
Navigate to your work item form customization page and add a Parent Details custom control.

Setup the following custom control properties:
- Set the 'FieldName' property to the 'Description' field. When something is filled in, the control will be collapsed.
- Set the 'ContentFields' property with semi colon seperated values of the fields that have to be displayed, like 'System.Description;Microsoft.VSTS.Common.AcceptanceCriteria'