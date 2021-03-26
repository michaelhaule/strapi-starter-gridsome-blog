# Strapi Starter Gridsome Blog

Gridsome starter for creating a great blog with Strapi.

![screenshot image](/screenshot.png)

This starter allows you to try Strapi with Gridsome with the example of a simple blog. It is fully customizable and due to the fact that it is open source, fully open to contributions. So do not hesitate to add new features and report bugs!

## Features

- 2 Content types: Article, Category
- 2 Created articles
- 3 Created categories
- Responsive design using UIkit

Pages:

- "/" to display every articles
- "/article/:id" to display one article
- "/category/:id" display articles depending on the category

## Getting started

Use our `create-strapi-starter` CLI to create your project.

```sh
# Using Yarn
yarn create strapi-starter my-project gridsome-blog

# Or using NPM
npx create-strapi-starter my-project gridsome-blog
```

The CLI will create a monorepo, install dependencies, and run your project automatically.

The Gridsome frontend server will run here => [http://localhost:8080](http://localhost:8080)

The Strapi backend server will run here => [http://localhost:1337](http://localhost:1337)

## Deploying to production

You will need to deploy the `frontend` and `backend` projects separately. Here are the docs to deploy each one:

- [Deploy Strapi](https://strapi.io/documentation/developer-docs/latest/setup-deployment-guides/deployment.html#hosting-provider-guides)
- [Deploy Gridsome](https://gridsome.org/docs/deployment/)

Don't forget to setup the environment variables on your production app:

For the frontend the following environment variable is required: 
- `GRIDSOME_STRAPI_URL`: URL of your Strapi backend, without trailing slash


Enjoy this starter!