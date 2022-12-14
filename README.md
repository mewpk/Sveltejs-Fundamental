# Sveltejs-Fundamental

## 1. Use the REPL
The Svelte REPL (Read-Eval-Print Loop) is the easiest way to begin. This is an interactive environment that allows you to modify code and instantly see the result.

You can choose from a list of examples, click the REPL link, and then tweak them until they do what you want.

You'll need to have Node.js installed, and know how to use the terminal

At some point, your app will outgrow the REPL. Click the download button to save a svelte-app.zip file to your computer and uncompress it.

Open a terminal window and set the project up...

```
cd /path/to/svelte-app
npm install
```

...then start up a development server:

```
npm run dev
```

This will serve your app on localhost:8080 and rebuild it with Rollup every time you make a change to the files in svelte-app/src.

## 2. Use degit

When you download from the REPL, you're getting a customised version of the sveltejs/template repo. You can skip messing around with zip files by using degit, a project scaffolding tool.

In the terminal, you can instantly create a new project like so:

```
npx degit sveltejs/template my-svelte-project
cd my-svelte-project
```
```
# to use TypeScript run:
# node scripts/setupTypeScript.js
```
```
npm install
npm run dev
```
This will create a new project in the my-svelte-project directory, install its dependencies, and start a server on http://localhost:8080.
