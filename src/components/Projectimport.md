```yml title="zerops-project-import.yml"
project:
  name: recipe-astro
  tags:
    - zerops-recipe

services:
  - hostname: app
    type: static@1.0
    enableSubdomainAccess: true
    buildFromGit: https://github.com/zeropsio/recipe-astro-static
```
