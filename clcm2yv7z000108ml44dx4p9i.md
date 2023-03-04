---
title: "Learning how to build a compiler: My journey"
datePublished: Sat Jan 07 2023 15:07:55 GMT+0000 (Coordinated Universal Time)
cuid: clcm2yv7z000108ml44dx4p9i
slug: learning-how-to-build-a-compiler-my-journey
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/g5f0BJq-FRs/upload/a52618e91266e220cebe6a4cd4e98a61.jpeg
tags: c, learning, compiler, learning-in-public

---

Learning how to program can feel like a large and complicated task. And for the most part, it is. Right now I'm pushing to better understand the C programming language. I have learned many other languages like Java, Python, and a little C++.

I was lucky to have a father that spent time teaching me how to write code, even if it was frustrating. He is not good with words, but he gave me a path to follow. Sometimes all your need is a starting point. If you are just starting on your programming journey, go and find a programming language that doesn't look too scary and just start.

Right now I am learning about compilers and trying to write my c compiler in the c programming language. It has been a fun task, I think it's funny that you can compile a language with itself. I learned about that technique, which is called bootstrapping from a YouTube video.

It has taken me a lot of time to get through the project, and I am only at the beginning. I have written part of the Lexer, which is the part of the compiler that breaks down the text into small chunks called tokens. These tokens contain the type of token it is; for example, "int" or "left parenthesis".

These tokens then get organized into an abstract syntax tree or AST. This is the part that I get confused about. The AST is used to organize the tokens logically, so for a = b + c, there would be a branch for b + c and then another branch to add that calc to a.

Taking on projects that are almost out of your reach is a great way to expand your thinking and problem-solving ability. While learning about lexers, I was in college and one of our projects needed to parse some data that we were scraping off of the web. I was able to bring in what I knew about lexers and parsing into the code that we wrote. Even though I didn't write a lexer exactly, I used the knowledge to build something different.

If you like this content, please like it. And if you want to be updated on my work, please sign up for the email list.

[Here is a link to the compiler Github repo](https://github.com/Yelk11/Compiler)

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/default-black.png align="left")](https://www.buymeacoffee.com/yelk11)