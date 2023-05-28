# AWS CDK Playground

Example of an AWS CDK template in different programming languages.

Example is an REST API built using:

-   API Gateway
-   Lambdas for endpoints.
-   DynamoDB table.

# REST API Endpoints

REST API allows client to manage contacts. Like those found in the contacts app on your phone.

List of every endpoint created by template.

## GET /contacts

Gets list of contacts from database.

## POST /contact

Adds contact to database.

## GET /contact/${contact_id}

Gets contact from database.

## PUT /contact/${contact_id}

Updates contact in database.

## DELETE /contact/${contact_id}

Deletes contact in database.
