# Welcome

You can view the current production version of this application at [https://explore-babylonjs-nextjs-typescript.vercel.app](https://explore-babylonjs-nextjs-typescript.vercel.app)

Core technologies powering this particular application include:

- [Next.js](https://nextjs.org)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org)
- [Vercel](https://vercel.com/)

Additional technologies include:

- [Babylon.js](https://www.babylonjs.com)

## Run the application

To run the application, simply install the required modules with `npm install` and then run `npm start` to launch the application.

This will allow you to view:

- The [Next.js](https://nextjs.org) application at [http://localhost:3000](http://localhost:3000)

## Starting from scratch

To create a new [Next.js](https://nextjs.org) application from scratch:

```sh
# Install next, react and react-dom in your project
$ npm install next react react-dom
```

Now, create your first page for Next.js:

```sh
# Create a pages directory for Next.js to use inside your project
$ mkdir pages

# Create a default page for your application
$ cd pages
$ touch index.js
```

```js
// pages/index.js
export default () => {
  return <div>Welcome to Next.js</div>
}
```

Run your server locally and verify that you can see your default page:

```sh
$ npm run dev
```

Your Next.js application should be available at [http://localhost:3000](http://localhost:3000) 🤓

### Adding TypeScript support to your Next.js app

To add support for [TypeScript](https://www.typescriptlang.org):

```sh
# Create an empty tsconfig.json file
$ touch tsconfig.json

# Try running your server, and you will see Next.js will guide you through installing the required packages
$ npm start
#
# > Running Dev Command “next dev --port $PORT”
# [ wait ]  starting the development server ...
# [ info ]  waiting on http://localhost:3000 ...
# It looks like you're trying to use TypeScript but do not have the required package(s) installed.
#
# Please install typescript, @types/react, and @types/node by running:
#
#        npm install --save-dev typescript @types/react @types/node
#
# If you are not trying to use TypeScript, please remove the tsconfig.json file from your package root (and any TypeScript files).

# Install the TypeScript dependencies
$ npm install --save-dev typescript @types/react @types/node
```

Next.js will automatically generate a TypeScript configuration file - `tsconfig.json` - as well as a Next.js types definition file at `next-env.d.ts`

## Third-party services

### Vercel

This project has been configured to automatically deploy to [Vercel](https://vercel.com/) - available at [https://explore-babylonjs-nextjs-typescript.vercel.app](https://explore-babylonjs-nextjs-typescript.vercel.app) - using the [Vercel for GitHub](https://vercel.com/github) integration.
