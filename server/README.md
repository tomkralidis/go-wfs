The server has the following url endpoints.  The source of the content for the endpoint is listed, server/routes.go maps requests to handlers & server/handlers.go encode the content appropriately for the response.

/ - root.go/root()
/conformance - conformance.go/conformance()
/api - openapi.go/api()
