# Redux Starter (github codespaces)

# THIS PROJECT IS FOR COMPLETE BEGINNERS :)

1. Make sure you have npm installed

2. Run these commands (to install the dependencies)

```npm install redux```

```npm install react-redux```

```npm install @reduxjs/toolkit```

3. Run npm run start

```npm run start```

If you've never used this before, here's a rundown:

* npm run is just a command
* You can make your own commands, for example, npm run meow (yes I added meow)

4. Check it out

5. Optional: How to publish it

**FIRST** 
* Go to settings on the github page (the home one)
(if you can't find it, it's https://github.com/replacewithyourusername/replacewithyourgithubprojectname/settings)
* Go to pages
* 

If you need to put your site on github pages, you should use gh-pages, you can find it here: [gh-pages](https://github.com/gitname/react-gh-pages)

Basically, do these steps (taken from react-gh-pages)

**Follow In Order**
1. Install gh-pages
```npm install gh-pages --save-dev```
2. Add homepage to package.json, for example, I would put https://zarmdev.github.io/Redux (CAPITAL R)
{
  "name": "my-app",
  "version": "0.1.0",
+ "homepage": "https://gitname.github.io/react-gh-pages",
  "private": true,
3. Add predeploy to package.json, literally just copy and paste the lines with a + into your scripts in package.json
"scripts": {
+   "predeploy": "npm run build",
+   "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
4. Commit changes
Open the terminal and enter:

```git add -A```

```git commit -m "message"```

```git push```

```npm run deploy```

If you don't know what deploy is, it's a made up command (the deploy part.)

Remember:

* npm run is just a command
* You can make your own commands, for example, npm run meow (yes I added meow)

If you want to know what it does under the hood, it runs npm run build which just makes the app ready to be run on a localhost/website

```npm run deploy``` **IS VERY IMPORTANT**

Now, 