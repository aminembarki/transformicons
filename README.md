Transformicons
======================
[![Build Status](https://travis-ci.org/grayghostvisuals/transformicons.svg?branch=master)](https://travis-ci.org/grayghostvisuals/transformicons)

![](https://dl.dropboxusercontent.com/u/41114960/github/transformicons/site.png)

**What's a transformicon?**

It's an animated symbol/button that morphs using either SVG or CSS and presented in a neatly packaged library.

We also provide a builder that gives developers the ability to select their preferred transformicons and output for finer control.

**What browsers do you support?**

IE10+, Chrome 36+, Safari 6+, Firefox 30+, Opera 22+, iOS 7+, Android 4+, Chrome for Android 38+

--

### Documentation
All of our documentation has been written in markdown and can be directly viewed on our site or under our [docs](https://github.com/grayghostvisuals/transformicons/tree/master/docs) directory. Feel free to reach out for help in the issue tracker making sure to title your issue as descriptive as possible. Please make sure you've also checked older issues that may relate to your question first before filing in order to avoid bogging down the issue tracker.

--

### Contributing
If you would like to contribute to the Transformicons project please make sure that anything feature related is isolated to a new branch and titled with the name of the feature being developed.

Local installation is dead simple. We use all local files and directories to run this project. This ensures you the developer don't need to  install anythign directly or globally to your system. Also take note we use libsass for preprocessing all of our Sass code.

**Install dependencies**

```bash
$ npm install
```

**Start a server and watch Sass files**

```bash
$ npm start
```

You'll find all our working files in the ``dist`` directory for Transformicons' JavaScript requirement and Sass for each transformicon. Any markup will be found in the ``site > templates`` directory. We use assemble to build our markup so make sure you're never editing a file with the ``.html`` extension. Assemble files use the ``.hbs`` file extension. These are the files you should be editing instead.

--

Props to [@bennettfeely](//twitter.com/bennettfeely) and [@SaraSoueidan](//twitter.com/SaraSoueidan).
Licensed under [MIT](//opensource.org/licenses/MIT)