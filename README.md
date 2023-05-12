# Web Interview Project

Using any tools provided let's build a TODO web appliaction. The app only needs to do a couple things. Primarily it is going to interact with the local sqlite3 database.


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

You need to install these packages below to run the application locally.
* [Node.js](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/lang/en/)

### Installation

1. Clone the repo
2. Install Node packages
    ```shell script
    yarn set version berry
    yarn
    ```
3. Clone `.env` file from `.env.example`, change the file content to yours.
4. Run database migration:
    * Run migration
    ```shell script
    npx sequelize-cli db:migrate
    ```
5. Start application in development
    ```shell script
    yarn dev
    ```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


### Built With
* [Next.js](https://nextjs.org)
* [Apollo Server](https://www.apollographql.com/docs/apollo-server)
* [Apollo Client](https://www.apollographql.com/docs/react)
* [Express](https://expressjs.com)
* [React](https://reactjs.org)
* [GraphQL](https://graphql.org)
* [Sequelize](https://sequelize.org)
* [SQLite](https://www.npmjs.com/package/sqlite3)
* [Material UI](https://material-ui.com)