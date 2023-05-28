# Changes for the hohmannr for awslabs/aws-lambda-go-api-proxy

- Added a fix for multiton/singleton header splitting while using `*httpadapter.HandlerAdapterALB` for ALB Responses
- Added a fix for multiton/singleton header splitting while using `*httpadapter.HandlerAdapterV2` for API-Gateway request
