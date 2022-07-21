---
ispreview: true
---
# Update the presence of a Microsoft Teams user based upon an inbound interaction

This Genesys Cloud Developer Blueprint explains how to set up Genesys Cloud and Microsoft Azure Active Directory to update a Genesys Cloud agent's presence in Microsoft Teams at the start and end of an inbound Genesys Cloud voice interaction.

When an Architect workflow receives an inbound interaction, a Microsoft Graph API call is sent to the Microsoft Teams user that is associated with the Genesys Cloud agent who is assigned to the interaction. The Microsoft Teams user's presence is set to "Do Not Disturb" when the voice interaction begins. When the interaction ends, the Microsoft Teams user's presence is set to "Available."

![Microsoft Teams agent view](images/msteams-workflow.png "Microsoft Teams presence update from an agent's point of view")

The following shows the end-to-end agent experience that this solution enables.

![End-to-end agent experience](blueprint/images/MSTeamsGCPresenceSyncBlueprint.gif "End-to-end agent experience")

To trigger Microsoft Teams presence updates from Genesys Cloud, you use several public APIs that are available from Genesys Cloud and Microsoft Graph. The following illustration shows the API calls between Genesys Cloud and Microsoft 365.

![The API calls between Genesys Cloud and Microsoft 365](blueprint/images/microsoft-teams-architect.png "The API calls between Genesys Cloud and Microsoft 365")

> View the full [Update the presence of a Microsoft Teams user based upon an inbound interaction](https://developer.mypurecloud.com/blueprints/) blueprint in the Genesys Cloud Developer Center.
