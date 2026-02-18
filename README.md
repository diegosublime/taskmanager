# taskmanager
Task manager project to practice devops and new .net features

- .NET (Backend)
Vertical Slice
Minimal API
Fluent Validation
Error handling, Result over exception (discriminated union)
Authorization and Authentication with JWT
Entity framework

- Database
  - SQL azure

- CI/CD
  - GitHub repo
  - GitHub Actions

- Server
  - Azure App service container
  - Docker Container 

- Observability
  - Application insights
  - Health checks
  - Alerts (Budget and Error)

- Infra as code
  - Terraform

- Edge
  - Cloudfare DNS, proxy and bot protection

## Requirements
- Create API to manage tasks. The API should expose methods for:
  - Authentication and authorization
    - Create Account (register): Capture email and password, confirmation code should be sent to provided email address
    - Account confirmation: provide email address and confirmation code to finish the account creation
    - Login: Only confirmed accounts can login, a jwt should be provided when email and correct password are provided.
   
  - Test endpoint: just to validate authentication and authorization 




