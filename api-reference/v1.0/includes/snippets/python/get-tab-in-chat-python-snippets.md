---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

query_params = TeamsTabRequestBuilder.TeamsTabRequestBuilderGetQueryParameters(
		expand = ["teamsApp"],
)

request_configuration = TeamsTabRequestBuilder.TeamsTabRequestBuilderGetRequestConfiguration(
query_parameters = query_params,
)

result = await graph_client.chats.by_chat_id('chat-id').tabs.by_tab_id('teamsTab-id').get(request_configuration = request_configuration)


```