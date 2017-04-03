---
layout: post
title: "Interview with webpack founder Tobias Koppers"
description: "Webpack is used by millions of developers worldwide. We had the chance to get an exclusive interview with the Author of webpack, Tobias Koppers."
modified: 2017-03-04
tags: [webpack, interview, tooling, javascript, grunt, gulp]
categories: [Tools]
image:
    feature: /webpack-cover.jpg
---

Tobias Koppers is a freelance software developer and consultant from Nuremberg. He became famous as author of webpack, which is used by millions of developers worldwide. His focus is on JavaScript development and open source projects. I had him in an exclusive interview, which I would not want to keep away from you. Have fun while reading it.  

<!-- more -->  

**Gregor: Hello Tobias, the whole JavaScript world talks about webpack. Even Google is based on it and has integrated it directly into the Angular CLI. I am also particularly proud of the fact that webpack comes from Nuremberg, so close to my hometown Ingolstadt (Germany). Tell us the story, how you came up with the idea and how webpack could spread so quickly.**  
  
**Tobias:** Hi Gregor. In fact, Google was also involved in the development, if only indirectly. Before I was addicted to JavaScript, I also worked with Java. There is a tool from Google that allows to develop a client-side web application in Java: Google Web Toolkit (GWT). This is a Java-to-JavaScript compiler for SPAs, which is also based on some Google applications.  
  
At the GWT there was one feature which I was totally into: Code Splitting. This allows, among other things, rarely used code to be loaded later. This feature is especially important for large applications to keep the initial load time small. I missed this feature in existing JavaScript-Tooling (2012) and this was when the idea of webpack was born.  
  
That means, webpack was created with the focus on code splitting, and in my opinion that was the reason why it was so common. With the growing size of web applications and the increased use of mobile devices (with weak network connectivity), they have grown the relevance of code splitting over time. Otherwise the desired performance is difficult to implement.  
  
**Gregor: Many compare webpack with task tools such as NPM scripts, Grunt and Gulp. Some have really found their replacement with webpack. I will use NPM scripts and webpack in future on. What’s your opinion on this and do you use a task tool in addition to webpack?**  
  
**Tobias:** NPM scripts are enough for me. In fact, it is not really correct to call webpack as a substitute for Grunt / Gulp. Grunt and Gulp belong to another category of tools like webpack. Grunt, Gulp and NPM scripts are task runner.  
  
Webpack is a Module Bundler. These are tools with different objectives. But it is true that webpack simplifies the necessary "tasks" to build a web application so far that it is possible to use an overkill TaskRunner like Grunt and Gulp and NPM scripts are sufficient. NPM is the replacement for Grunt and Gulp.  
  
However, task runner still have their own reasoning for other tasks besides the pure building of the web application: deployment, linting, version management, etc.  
  
**Gregor: With my JavaScript trainings, my participants are telling me over and over again, how difficult it is to start with webpack. Did you get similar feedback already? If so, do you already have ideas on how to improve that?**  
  
**Tobias:** Yes, indeed, this feedback comes. However, many users also say that once it has "clicked", it is actually quite simple to use. Anyone who can "web" even says that it is easier than the previous tools.  
  
I believe this feedback is due to the fact that the concepts of webpack differ significantly from the concepts of other tools. Especially when migrating from Grunt / Gulp to webpack. Task runner have a more imperative configuration, that is describing the steps to be performed by the task runner. Webpack, on the other hand, has a declarative configuration, that means, it does not describe the steps to be executed by webpack, but only describes the way in which these steps are to be executed or how the result has to look.  
  
**Gregor: What's on your agenda? What features are planned for the next webpack version?**  
  
**Tobias:** That's not quite clear yet. There are so many things that are possible. Just to mention a few exciting points:
* Scope Hoisting: small and more powerful way to connect the modules  
* WebAssembly: Support for binary code in the WebApp  
* Persistenter cache: Faster initial compilation  
* CSS (and HTML) as first-class citizen: More support for stylesheets (and HTML)  
* And many exciting little things  
  
The users and sponsors decide in which order they will be targeted. We have a voting page, where you can vote for the next points. Everyone gets an influence every day and sponsors and contributors get golden points of influence for donations and contributions. This happens from the motivation of sponsors and contributors, because they wanted to give something back. In addition, it is of course interesting what users want the most.  
  
**Gregor: Can you give us a top best practice tip on webpack?**  
  
**Tobias:** Use On-Demand-Loading. It is super easy to use and it works out incredibly.  
  
**Gregor: What are your personal goals? Will we all soon read, that you're going to work at Google in Mountain View? ;)**  
  
**Tobias:** I don’t think so. I will be working as a freelancer soon. I will try to work as much as possible on open source and finance the whole thing through donations. Since donations are usually not enough, I will finance the rest through commissioning or consulting. I'm already curious how this works. Maybe there is a sponsor for me, who will finance a few additional weeks Open Source (hey Google ;)).  
  
The effort to maintain an open source project is often underestimated. Currently, Code Reviews and Issues take 80% of my time. I neither have enough time to write code myself, nor to refactor. I even have to leave pull requests behind for a while. I need to find the time to look at them in detail. This is not really motivating the contributor of course. I think this will change, as soon as I work on webpack full time. Hopefully I have more time to write more code.  
  
**Gregor: Thank you very much for taking the time for the interview! Thanks also for webpack, which supports us as JavaScript developers extremely. I love your tool!**  
  
**Tobias:** You’re welcome. My thanks goes back to the community. Webpack is not "my" tool, it is designed by more than 500 contributors. Webpacks success is also because of its great ecosystem.

