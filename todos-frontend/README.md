This is a [Vite](https://vitejs.dev) project bootstrapped with [`create-wagmi`](https://github.com/wevm/wagmi/tree/main/packages/create-wagmi).

# Building the Frontend of the TODO APP
You will be able to:

- Build a frontend with wagmi and React.
- Use wagmi to generate React hooks for contract calls.
- Call smart contract functions from the frontend.

You already have built the TODO smart contract with Solidity. In this tutorial, you will build a frontend client using NodeJS, React, and wagmi.sh.

Preparing the Project 
`npm create wagmi@latest todos-frontend
`
Select react and variant vite

Head to todos-frontend and run
`npm install --save-dev @wagmi/cli
`
This install the wagmi-cli tools and helps to generate React hooks and functions from the Foundry Project.

To generate the wagmi config
`npx wagmi init` 

Open the wagmi.config.ts and replace with this code 

Run this to generate custom react hooks
`npx wagmi generate`
This should generate a new file at src/generated.ts containing the custom React hooks.

Run the frontend app `npm run dev`

Now do the changes in the frontend code, to do the operations like 
- create a todo
- update a todo
- delete a todo 
