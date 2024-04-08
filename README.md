# vrasidas
A friendly ai for kids


# prepare the project
## init
yarn init 
yarn add @types/node typescript 
yarn add -D ts-node

yarn tsc --init --rootDir src --outDir ./bin --esModuleInterop --lib ES2019 --module commonjs --noImplicitAny true

make a src dir and a bot.ts file in it

### build
yarn tsc && node ./bin/bot.js

### run for development
yarn ts-node src/bot.ts

