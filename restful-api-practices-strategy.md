# RESTful Practices

## Routes Naming Convention:

- Use plural nouns: Name your routes using plural nouns to represent collections of resources. For example, `/users` instead of `/user`.
- Use lowercase letters: Use lowercase letters for all route names to ensure consistency.
- Use hyphen or underscore: When using multiple words in a route, you can separate them using either hyphens or underscores. For example, `/user-reviews` or `/user_reviews`.
- Avoid verbs in route names: Use nouns instead of verbs in your route names. Verbs can be expressed through the HTTP methods (GET, POST, PUT, DELETE, etc.) that you use with the routes.

## Documentation Guide:

Proper documentation helps developers understand and use your API effectively. Here are some guidelines for documenting your RESTful API:

- Use Swagger for API documentation: Maintain API documentation using Swagger or OpenAPI specifications. Swagger provides a standardized way to describe your API endpoints, request/response formats, and parameters.
- Provide an overview: Start with an overview of your API, including its purpose and the resources it provides.
- Document endpoints: Use Swagger annotations or comments in your code to provide detailed information about each endpoint, including the URL, supported methods, request/response format, and any required headers or parameters.
- Include examples: Include examples of how to use each endpoint, showcasing both successful and error responses.
- Explain error codes: Document the error codes that your API may return and their corresponding meanings. Include a description of how to handle errors and any error response formats.

## Error Codes:

Here are some common HTTP status codes that you can use for error responses:

- 400 Bad Request: The request is malformed or invalid.
- 401 Unauthorized: Authentication is required or has failed.
- 403 Forbidden: The authenticated user is not authorized to access the requested resource.
- 404 Not Found: The requested resource does not exist.
- 500 Internal Server Error: An unexpected error occurred on the server.

## Payload Structure:

A common payload structure for API responses can be as follows:

```json
{
    "status": "success/fail",
    "message": "Additional information about the request status or error message",
    "data": {
        // The actual data related to the request
    }
}
