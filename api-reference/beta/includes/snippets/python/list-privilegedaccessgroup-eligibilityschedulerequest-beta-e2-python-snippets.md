---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = EligibilityScheduleRequestsRequestBuilder.EligibilityScheduleRequestsRequestBuilderGetQueryParameters(
		select = ["principalId","action","groupId"],
)

request_configuration = EligibilityScheduleRequestsRequestBuilder.EligibilityScheduleRequestsRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.identity_governance.privileged_access.group.eligibility_schedule_requests.get(request_configuration = request_configuration)


```