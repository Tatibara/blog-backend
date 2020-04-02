## GraphQL Basics

### What is GraphQL

GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL provides a complete and understandable description of the data in your API, gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools. [[https://graphql.org/](https://graphql.org/)]

There is [specification](http://spec.graphql.org/) for GraphQL.

There are two type of Types:
* Scalar Types: String, Boolean, Int, Float, ID
* Non Scalar Types: Objects and Arrays

In this project I am using [graphql-yoga](https://www.npmjs.com/package/graphql-yoga) fully-featured GraphQL Server with focus on easy setup, performance & great developer experience. [[graphql-yoga](https://www.npmjs.com/package/graphql-yoga)]
For the subscriptions this library uses [graphql-subscriptions](https://github.com/apollographql/graphql-subscriptions).

### Useful links

* 36 most important GraphQL [concepts](https://36-concepts-graphql.netlify.com/) to know
* A weekly [newsletter](https://www.graphqlweekly.com/) of the best news, articles and projects about GraphQL
* Harnessing the power of TypeScript & GraphQL with [Nest.js](https://docs.nestjs.com/graphql/quick-start)
* [Comparison](https://blog.apollographql.com/graphql-vs-rest-5d425123e34b) between GraphQL and REST

### How to run the project

To run the project execute `yarn start`

The GraphQL Playground is running under `http://localhost:4000/`
