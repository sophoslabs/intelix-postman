# SophosLabs Intelix - Postman collection

[SophosLabs Intelix](https://aws.amazon.com/marketplace/pp/B07SLZPMCS) is a cloud-based threat intelligence and analysis
platform, allowing programmers to tap into the technology behind SophosLabs through a simple, RESTful API, ready to
integrate into any application. Identify known and potential threats, reduce unknowns, and derive verdicts and JSON and
HTML intelligence reports in seconds.

You can find here a Postman collection for the SophosLabs Intelix APIs.

Sophos provides the following files:
 * [Intelix.postman_collection.json](Intelix.postman_collection.json): The API collection.
 * Environments:
   * [Intelix-de.postman_environment.json](Intelix-de.postman_environment.json): The Postman environment for Germany.
   * [Intelix-us.postman_environment.json](Intelix-us.postman_environment.json): The Postman environment for US.

## How to use the API

First, you have to obtain an access token to call the Intelix APIs. You have to use the **Cognito AccessToken** endpoint
to get one. Then, you can use the other APIs as the access token will be populated by Postman to those API calls.

Note: the access token expires after one hour.
