# Nautobot App Template Guidance

This project follows the Nautobot cookiecutter standards for creating new Nautobot Apps. The official templates provide a Docker Compose development environment and enforce common project structure.

## Generating a New App

Use [Cookiecutter](https://github.com/cookiecutter/cookiecutter) to create a new app skeleton:

```shell
cookiecutter \
  --output-dir=./outputs \
  --directory=nautobot-app \
  https://github.com/nautobot/cookiecutter-nautobot-app
```

Refer to the template documentation for the meaning of each prompt. After generation, replace the placeholder logo file and remove all blocks marked `Developer Note - Remove Me!`.
