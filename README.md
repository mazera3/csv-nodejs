# Tecnologias Utilizadas
- insomnia
- vscode
- nodejs
- bibliotecas: express, prisma, multer

# Iniciar Projeto Csv-node
- yarn init -y (cria o pacote package.json)
- Instalar express, prisma e typescript:
  - `yarn add express @prisma/client`
  - `yarn add typescript @types/express @types/node ts-node-dev -D`
  - `yarn add prisma -D`
  - Criar pasta/arquivo pelo terminal: `mkdir src && touch src/server.ts`
  - Criar tsconfig.json: `yarn tsc --init`
  - Criar gitignore pelo terminal: `touch .gitignore`
  - Adicionar arquivos e pastas pelo terminal: `echo -e "node_modules/\n.env" >> .gitignore`
  - Rodar yarn dev (rodar app)

# Multer
- Instalar biblioteca [multer](https://www.npmjs.com/package/multer)
- `yarn add multer`, `yarn add @types/multer -D`
- Criar arquivo de rotas: src/routes.ts

# Prisma
- iniciar: `yarn prisma init`
- Criar banco de dados mysql: `csv-nodejs`
- Editar schema.prisma
- Rodar: yarn prisma migrate dev --name create_products
- Criar pasta/arquivo: src/database/client.ts
