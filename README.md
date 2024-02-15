## Step by Step

1. `npm i -g @nestjs/cli` (Se já não tiver instalado)
2. `nest new project-name`
3. `npm i --save @nestjs/platform-fastify` (para usar o fastify no lugar do express)
    - 1. Precisaremos usar o adapter [documentação oficial](https://docs.nestjs.com/techniques/performance)
    - 2. 