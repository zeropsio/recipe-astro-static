```yml title="zerops.yml"
zerops:
  - setup: app
    build:
      base: nodejs@20
      buildCommands:
        - pnpm i
        - pnpm build
      deployFiles:
        - dist/~
      cache:
        - node_modules
        - pnpm-lock.yaml
    run:
      base: static
```
