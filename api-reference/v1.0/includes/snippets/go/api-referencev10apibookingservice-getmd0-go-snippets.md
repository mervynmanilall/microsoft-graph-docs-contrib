---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



services, err := graphClient.Solutions().BookingBusinesses().ByBookingBusinessId("bookingBusiness-id").Services().ByBookingServiceId("bookingService-id").Get(context.Background(), nil)


```