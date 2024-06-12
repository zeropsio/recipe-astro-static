```yml
project:
   name: astro

  services:
   - hostname: astrostatic
    type: nodejs@18
    buildFromGit: https://github.com/fxck/zerops-astro-static
    ports:
      - port: 3000
        httpSupport: true
    enableSubdomainAccess: true
    minContainers: 1
```
