---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = UnifiedGroupSource(
	included_sources = SourceType.Mailbox,
	additional_data = {
			"group@odata_bind" : "https://graph.microsoft.com/v1.0/groups/93f90172-fe05-43ea-83cf-ff785a40d610",
	}
)

result = await graph_client.security.cases.ediscovery_cases.by_ediscovery_case_id('ediscoveryCase-id').custodians.by_custodian_id('ediscoveryCustodian-id').unified_group_sources.post(body = request_body)


```