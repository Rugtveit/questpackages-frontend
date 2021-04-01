<h1 align="center">QuestPackages front-end</h1>

<h2 align="center">

A website that shows packages from QuestPackages [Backend](https://github.com/Rugtveit/questpackages-backend). 

Website made in [Next.js](https://nextjs.org/) and [Typescript](https://www.typescriptlang.org/)

</h2>
<h1> Usage </h1>
Clone the repo

    git clone https://github.com/Rugtveit/questpackages-frontend

Get in the repo folder 

    cd questpackages-frontend

Install required modules

    npm install

Create a local enviornment file

    touch .env.development.local

Open up file and add your [Github Token](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) 

The token is required to authenticate with [Github GraphQL API](https://docs.github.com/en/graphql/guides/forming-calls-with-graphql#authenticating-with-graphql)

    GITHUB_TOKEN = YOUR_TOKEN_HERE

Starting the website

    yarn dev

or

    npm run dev

## Note: The [Backend](https://github.com/Rugtveit/questpackages-backend) needs to be running for it to work! 


