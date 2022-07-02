# {{cookiecutter.project_name}}

## Development
1. First define your API definition in the ```openapi.yml``` file. There is an example definition included.
2. Generate the API Code for FastAPI by running ```gen.sh````
3. On successful execution of this, there will appear an ```app```folder. In there the project's source code is generated
4. Continue your development inside these files now. Use the ```.openapi-generator-ignore``` to disable the generation of certain artifacts of your new API.

### Debugging
This template has been adapted for use with VSCode. Please have the following extensions enabled:
* Python
* Pylance
* Docker

Simply hit <F5> and the docker container will be built and you can do live updates on your code.
 
