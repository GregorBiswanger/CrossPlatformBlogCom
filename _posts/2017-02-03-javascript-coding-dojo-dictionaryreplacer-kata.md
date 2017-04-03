---
layout: post
title: "JavaScript Coding Dojo: The DictionaryReplacer Kata"
description: "This kata is about making a simple string replacer."
modified: 2017-03-02
tags: [TDD, BDD, Jasmine, VSCode, TypeScript, Nodejs, Debugging]
categories: [Coding-Dojo-Katas]
image:
    feature: /JavaScript-Coding-Dojo-cover.jpg
---

A dojo is the exercise room of Japanese martial arts. The exercises itself are called kata. The coding dojo is about mastering an exercise (kata). According to the motto "Learning by doing". The cross-platform blog will now regularly publish JavaScript Katas.  

## The DictionaryReplacer Kata
This kata is about making a simple string replacer. It is inspired by Corey Haines Lightning talk about practicing. Create a method that takes a string and a dictionary, and replaces every key in the dictionary pre and suffixed with a dollar sign, with the corresponding value from the Dictionary.  
   
<!-- more -->  
  
**Tests:**  
**input:** "", **dictionary:** empty, **output:** ""  
  
**input:** "\$temp\$", **dictionary:** ["temp", "temporary"], **output:** "temporary"  
  
**input:** "\$temp\$ here comes the name \$name\$", **dictionary:** ["temp", "temporary"] ["name", "John Doe"], **output:** "temporary here comes the name John Doe"  

**Difficulty:** Simple  
**Duration:** Ca. 5-20 Minutes  
**Source:** [http://codingdojo.org/kata/DictionaryReplacer/](http://codingdojo.org/kata/DictionaryReplacer/ "The DictionaryReplacer Kata"){:target="_blank"}  
  
  
## Preperations for the start  
The following is required for the project:    
- [Node.js](http://www.nodejs.org "www.nodejs.org"){:target="_blank"} (runs on Windows, Mac and Linux)  
- TypeScript  
  type `npm install typescript –g` in the terminal   
- [Visual Studio Code](http://code.visualstudio.com "http://code.visualstudio.com"){:target="_blank"} (runs on Windows, Mac and Linux)  
  
There has already been deposited a complete exercise project on GitHub for you:    
  
`git clone https://github.com/GregorBiswanger/KataDictionaryReplacer.git`  

Then install all necessary modules within the project with `npm install`.  
  
> You have never worked with TypeSript before? Don`t worry! TypeScript == JavaScript, and you can use your existing JavaScript knowledge without problems. The advantages? Go and find it out by yourself in the code exercise. ;) A significant difference is that the file ending is * .TS. The TypeScript created javascript and source map files are hidden for this exercise. This provides a better overview. In the file system, however, these exist.  
  
## The start  
1. Open the project with Visual Studio Code  
2. Start the TypeScript compiler with the key combination `[ctrl] + [shift] + [b]`  
3. At the terminal, write `npm test` within your project  

Now the testrunner Jasmine is running. It notices file changes automatically. If you have a second monitor, there is the ideal place for the terminal. This allows you to observe the current status during development.   
  
<figure>
	<a href="/images/04/vscode-npm-test.jpg"><img src="/images/04/vscode-npm-test.jpg" alt="npm start"></a>
</figure>
  
## The process
Important with Coding Dojos is, to solve every task step by step. This principle is not easy for many developers. But exactly this is, what coding dojos are teaching us.  
  
Which tasks have to be performed step by step can be found in the `spec` directory. The actual programming takes place in the `src` folder.  
  
## Debugging
The project already has all the necessary Visual Studio Code settings, so you can easily debug within the tests or your own code. Simply set the breakpoint with the `[F9]`-key and start the debugging with `[F5]`.  
  
<figure>
	<a href="/images/04/vscode-jasmine-debugging.jpg"><img src="/images/04/vscode-jasmine-debugging.jpg" alt="Unit Test Debugging"></a>
</figure>
  
## Rules
-	Solve the kata until all tests are green  
-	Then copy your solution here on jsfiddle.net:  
  **[https://jsfiddle.net/GregorBiswanger/n6zm9wz7/](https://jsfiddle.net/GregorBiswanger/n6zm9wz7/ "jsfiddle.net"){:target="_blank"}**  
-	Click on the "Update" button in the upper left corner and comment on your link here at this blog post  
-	Not till then, you are allowed to compare your solution with already commented solutions  
  
<figure>
	<a href="/images/04/jsfiddle-typescript-jasmine.jpg"><img src="/images/04/jsfiddle-typescript-jasmine.jpg" alt="jsfiddle kata mit typescript und jasmine"></a>
</figure>
  
## Let's get ready to rumble!
With my JavaScript Workshops I always like to do Coding Dojos with my participants. I love to evaluate the different solutions afterwards. I`m excited about how you will solve the task. And now: Let's get ready to rumble!  


