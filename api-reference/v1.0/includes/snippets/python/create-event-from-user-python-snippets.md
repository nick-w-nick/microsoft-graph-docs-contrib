---
description: "Automatically generated file. DO NOT MODIFY"
---

```python

# THE PYTHON SDK IS IN PREVIEW. FOR NON-PRODUCTION USE ONLY

graph_client = GraphServiceClient(request_adapter)

request_body = Event(
	subject = "Let's go for lunch",
	body = ItemBody(
		content_type = BodyType.Html,
		content = "Does noon work for you?",
	),
	start = DateTimeTimeZone(
		date_time = "2017-04-15T12:00:00",
		time_zone = "Pacific Standard Time",
	),
	end = DateTimeTimeZone(
		date_time = "2017-04-15T14:00:00",
		time_zone = "Pacific Standard Time",
	),
	location = Location(
		display_name = "Harry's Bar",
	),
	attendees = [
		Attendee(
			email_address = EmailAddress(
				address = "samanthab@contoso.onmicrosoft.com",
				name = "Samantha Booth",
			),
			type = AttendeeType.Required,
		),
	]
	allow_new_time_proposals = True,
	transaction_id = "7E163156-7762-4BEB-A1C6-729EA81755A7",
)

request_configuration = EventsRequestBuilder.EventsRequestBuilderPostRequestConfiguration(
headers = {
		'Prefer' : "outlook.timezone=\"Pacific Standard Time\"",
}

)

result = await graph_client.me.events.post(body = request_body, request_configuration = request_configuration)


```