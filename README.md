# Azure functions for enriching BontAi AI agent's set of custom functions for use within Virtuals
Functions for BontAI to enrich agent behavior

If you want to clone this you'll need dotnet core to run it. 
I suggest hosting and running in Microsoft Azure -> Azure Functions
It makes use of the Azure Keyvault for storing secrets, you'll need to add in your own.

Note: BontAi is developed to help reuniting pets with their owners.
However, this repository holds functions that can be independently used for other causes.

Features on Facebook:
- Create Post
- Search posts via tags 
- Search groups via tags
- Join group
- Read group posts
- Create Post in Group
- Reply to Post in Group

