# Dackboard

Dackboard is a modern platform that allows anyone to create games or tournaments for Dart games.  

---
**<p align="center">
This is the meta repository. It contains conception, guidelines, tooling and project management.<br/>
Check out the [client], [server] or [api docs] repositories**

[client]:https://github.com/dackboard/dackboard-client
[server]:https://github.com/dackboard/dackboard-server
[api docs]:#
</p>

---
| [Server Repository](https://github.com/dackboard/dackboard-server) | [Client Repository](https://github.com/dackboard/dackboard-client) | [Scoreboard Repository](#) |
|:---------------------:|:-------------------:|:------:|
| [![Coverage Status](https://coveralls.io/repos/github/dackboard/dackboard-server/badge.svg?branch=master)](https://coveralls.io/github/dackboard/dackboard-server?branch=master) [![Build Status](https://travis-ci.org/dackboard/dackboard-server.svg?branch=master)](https://travis-ci.org/dackboard/dackboard-server) | *insert badges* | *to be started* |
  

## Conception

### Basic Architecture
![Architecture](https://i.imgur.com/3RX8vg8.png)
- The SQL Database stores persistent data such as completed games & tournaments with computed data
- The noSQL Database stores temporary data such as active/running games and tournaments,
  data stored in this database is more dynamic and not computed yet (happens when finishing a game and the dataset is transferred to the SQL database)
- The server connects all services together
- The client is used to input data about games, tournaments and also provides the live-data for a currently running game
- The scoreboard is used to display data such as tournament stats/trees and current game scores

## Contributing
The backend is a JSON API server built using Node, TypeScript and Express. The frontend is a React App built with TypeScript. 

If you want set up a local development environment follow these steps:  
1. Read our [Contribution Guide](/CONTRIBUTING.md)
2. Install node
3. Clone the git repositories
4. Run `npm install` to install the dependencies
5. Follow the setup instructions of each repository

## Screenshots
*will be inserted*

## License
*will be inserted soon too*