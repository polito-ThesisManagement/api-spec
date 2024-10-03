# PoliTO Thesis Management API Spec
The OpenAPI specification for the REST API for thesis management of Politecnico di Torino.

## How to obtain a human-readable interface
If you are accustomed to using Postman, you can just import the .yaml file containing the specification.

Alternatively, you can start a Docker container of swagger-ui directly on your computer by running: 
```bash
docker-compose up
``` 
By default, the web interface will start on port 8080.

## About OpenAPI
These definitions provide a single point of truth that can be used end-to-end:

- **Planning** Shared during product discussions for planning API functionality
- **Implementation** Inform engineering during development
- **Testing** As the basis for testing or mocking API endpoints
- **Documentation** For producing thorough and interactive documentation
- **Tooling** To generate server stubs and client SDKs.

## Running a mock API
We suggest using [Prism](https://github.com/stoplightio/prism) to run a mock version of this API.

After installing it, you can start a mock server with the following command:
```bash
prism mock -h YOUR-LOCAL-IP ./openapi.yaml
```

## Resources

- [OAS3 Specification](http://spec.openapis.org/oas/v3.0.3)
- [OAS3 Examples](https://github.com/OAI/OpenAPI-Specification/tree/master/examples/v3.0)