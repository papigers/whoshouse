# Instagram-clone

Fullstack instagram clone made with:

*   [React-native](https://facebook.github.io/react-native/)
*   [Apollo](https://www.apollographql.com/)
*   [React-navigation](https://reactnavigation.org/)
*   [Styled-components](https://www.styled-components.com/)
*   [Node js / Express ](https://expressjs.com/)
*   [GraphQL](https://graphql.org/)
*   [Typeorm / postgreSQL](http://typeorm.io/#/)

![login](./client/resources/login.png)
![feed](./client/resources/feed.png)
![explore](./client/resources/explore.png)
![camera](./client/resources/camera.png)
![notifications](./client/resources/notifications.png)
![profile](./client/resources/profile.png)
![comments](./client/resources/comments.png)

## How to run local

### Client

1 `git clone https://github.com/MarcinMiler/instagram-clone.git`

2 `cd/instagram-clone/client && yarn`

3 `yarn start`

4 In apollo.js you need to change IP address to your server.

### Server

You need to have installed postgreSQL, and configure ormconfig.json file (database connection) to run server localy.

1 `cd instagram-clone/server && yarn`

2 `yarn start`

## Tests

1 `cd instagram-clone/server`

2 `yarn test`

## Todo

*   Images hosting
*   Improve UI and UX
*   Add subscriptions
