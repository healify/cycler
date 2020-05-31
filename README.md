start server
serverless deploy

local dev
serverless invoke local --function graphql -p events/basic.json

prerequisite
https://www.apollographql.com/docs/apollo-server/deployment/lambda/
