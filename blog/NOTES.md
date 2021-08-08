# Blog
An app for create and submit blogs

## What you will learn
* [NEXT.js](https://nextjs.org/) - A server side rendering framework

## What is expected of you
* Basic terminal usage (like cd, ls, touch)
* Javascript upto ES6
* React.js (basics should be enough)
* TypeScript

## Steps to follow along
1. Install pre requisites: 
	* [node](https://nodejs.org/en/download/) (preferably with [nvm](https://github.com/nvm-sh/nvm) )
	* [yarn](https://classic.yarnpkg.com/en/docs/install/#debian-stable) package manager	
	* [create-next-app](https://create-next-app.js.org/installation/)

2. On your terminal, where you want to start the project, create your app with this:
	` $ yarn create next-app --typescript `

3. You can now view the app by using:
	` $ yarn dev `
	This is live-reload so, all code changes will be reflected (just like React)

4. Please read a brief overview of the folder structure below. (TODO)

5. The `./pages/` (folder) keeps track of the routes. 
	Add contents for the [/](http://localhost:3000/) (route) in index.js. 

6. Created `blog/` inside `pages/`. These files would be accessible by [/blogs/1](http://localhost:3000/blogs/1) and [/blogs/2](http://localhost:3000/blogs/2)