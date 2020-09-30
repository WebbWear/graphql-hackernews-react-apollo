React & Apollo Tutorial

This is the sample project that belongs to the React & Apollo Tutorial on How to GraphQL.
How to use
1. Clone repository

git clone https://github.com/howtographql/react-apollo/

2. Install dependencies & Deploy the Prisma database API

To install the Prisma CLI globally with Yarn, use the following command:

yarn global add prisma

Also, run the following commands:

cd react-apollo/server
yarn install
prisma deploy

Then, follow these steps in the interactive CLI wizard:

    Select Demo server
    Authenticate with Prisma Cloud in your browser (if necessary)
    Back in your terminal, confirm all suggested values

Alternative: Run Prisma locally via Docker
3. Start the server

To start the server, all you need to do is execute the start script by running the following command inside the server directory:

yarn start

    Note: If you want to interact with the GraphQL API of the server inside a GraphQL Playground, you can navigate to http://localhost:4000.

4. Run the app

Now that the server is running, you can start the React app as well. The commands need to be run in a new terminal tab/window inside the root directory react-apollo (because the current tab is blocked by the process running the server):

yarn install
yarn start

You can now open your browser and use the app on http://localhost:3000.
About
No description, website, or topics provided.
Resources
Readme
License
MIT License
Releases
No releases published
Packages
No packages published
Contributors 11

    @nikolasburk
    @swcarlosrj
    @marktani
    @Arieg419
    @anku255
    @thewillwill
    @incon
    @dstroot
    @oprearocks
    @bodazhao
    @qucode1

Languages

JavaScript 94.3%
HTML 3.5%

    CSS 2.2% 

