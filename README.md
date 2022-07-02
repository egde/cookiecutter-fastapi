# Cookiecutter - FastAPI

This is a cookiecutter template for APIs using FastAPI.

The setup here is taking up an opinionated approach by expecting the developer to first specify the interface of the API using the OpenAPI standard. From the OpenAPI specification the server code is generated based on the FastAPI framework. The development is done via Visual Studio Code inside of a Docker Container. This template will generate the necessary tasks and launch configurations for running and debugging the API from VS Code inside of the container.

## How to use
1. Run the cookiecutter command as such
```cookiecutter gh:egde/cookiecutter-fastapi```
2. Adapt the ```openapi.yml```
3. Run ```./gen.sh````
4. Hit <F5> to run the generated FastAPI API implementation
5. Adapt your code in ```app/src/``` and the new code will be reloaded
