---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

// Code snippets are only available for the latest version. Current version is 5.x

var graphClient = new GraphServiceClient(requestAdapter);

var requestBody = new TeamsAppSettings
{
	OdataType = "#microsoft.graph.teamsAppSettings",
	IsUserPersonalScopeResourceSpecificConsentEnabled = true,
};
var result = await graphClient.Teamwork.TeamsAppSettings.PatchAsync(requestBody);


```