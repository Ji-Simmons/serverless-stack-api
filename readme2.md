# 5c985780-d463-11ea-aa2b-a7fa3edf3a85\

# Publishable key
# pk_test_51HBWwyDl68TNVtDpo4NMErdnIA8F4dxggMBb2nVzgrBH1McqjZQJRGI3z66lBxDU9DRGKzunjdl0PeH5MBlqyo3900O5Vk3XCY
# Secret key
# sk_test_51HBWwyDl68TNVtDpz0dLWWzIzzUl4RjriQ5kAIGUFKdARvINQmHNuvWZyTBx40dpalfVjOEea7Q01okCeD8w3nmF00Uh8LQpKO

# Service Information
# service: notes-app-api
# stage: prod
# region: us-east-2
# stack: notes-app-api-prod
# resources: 43
# api keys:
#   None
# endpoints:
#   POST - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/notes
#   GET - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/notes/{id}
#   GET - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/notes
#   PUT - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/notes/{id}
#   DELETE - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/notes/{id}
#   POST - https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod/billing
# functions:
#   create: notes-app-api-prod-create
#   get: notes-app-api-prod-get
#   list: notes-app-api-prod-list
#   update: notes-app-api-prod-update
#   delete: notes-app-api-prod-delete
#   billing: notes-app-api-prod-billing
# layers:
#   None

# cognito user Pool Id us-east-2_yyXIFPeiW
# Pool ARN arn:aws:cognito-idp:us-east-2:859147642469:userpool/us-east-2_yyXIFPeiW

# cognito App client ID 2o9aiosntrvbd7krj95pma3rse

#Identity pool ID: us-east-2:19f8dbc8-53fb-4b3c-bed3-d859da557586

# npx aws-api-gateway-cli-test \
# --username='ji.simmons@yahoo.com' \
# --password='Passw0rd!' \
# --user-pool-id='us-east-2_yyXIFPeiW' \
# --app-client-id='2o9aiosntrvbd7krj95pma3rse' \
# --cognito-region='us-east-2' \
# --identity-pool-id='us-east-2:19f8dbc8-53fb-4b3c-bed3-d859da557586' \
# --invoke-url='https://lfaxcjefu1.execute-api.us-east-2.amazonaws.com/prod' \
# --api-gateway-region='us-east-2' \
# --path-template='/notes' \
# --method='POST' \
# --body='{"content":"hello world","attachment":"hello.jpg"}'


  