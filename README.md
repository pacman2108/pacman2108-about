 # pacman.vercel.app 

 This repo contains the files for my website

------

 # Steps:

 Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte);

 ## Creating a project

 If you're seeing this, you've probably already done this step. Congrats!

 ```
 # create a new project in the current directory
 npm init svelte@next
 
 # create a new project in my-app
 npm init svelte@next my-app (replace my-app with your project's name (replace spaces with -))
 
 cd <project name>
 
 # Install node modules for fluent-svelte
 npm i fluent-svelte svelte-focus-trap
 
 npm i sass node-sass
 npm i focus-trap
 ```

  Note: the `@next` is temporary

 ## Deployment

 Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

 ```
 npm run dev
 
 # or start the server and open the app in a new browser tab
 npm run dev -- --open
 ```

 ## Building

 Before creating a production version of your app, install an [adapter](https://kit.svelte.dev/docs#adapters) for your target environment. Then:

 ```
 npm run build
 ```

  You can preview the built app with `npm run preview`, regardless of whether you installed an adapter. This should *not* be used to serve your app in production.
