---
title: "Top 5 skills for software engineers"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Software
  - Engineering
  - Code quality
---

<figure>
    <img src="{{ site.url }}{{ site.baseurl }}/images/posts/softwareengineer.jpg" alt="Software engineer picture" itemprop="image" />
</figure>

*Software engineers* are responsible for designing, developing, maintaining, testing, and evaluating software and systems that make computers or anything containing software work. Nowadays, *software engineering* is one of the most promising careers and it is easy to notice due to the huge quantity of job offers, headhunters, etc. out there. If you really want to become a good software enginner here are five of the most important skills you will need to consider:

### 1. Keep it simple
The KISS principle ("Keep it simple, stupid", as a design principle noted by the U.S. Navy in 1960.) is a rule of thumb that is present in lots of areas. It was referred several times along the history: 

- "Simplicity is the ultimate sophistication" (Leonardo da Vinci)
- "It seems that perfection is reached not when there is nothing left to add, but when there is nothing left to take away" (Antoine de Saint Exupéry)
- "Simplify, then add lightness" (Colin Chapman, the founder of Lotus Cars)

It states that most systems work best if they are kept simple rather than made complicated. Software development is one of the fields in which is very well applied.

In the engineering field and specially in software engineering try do not reinvent the wheel:

- Follow software patterns that have been proven during years. 
- Reuse code from others and manage your priorities. I know that sometimes it will hurt your ego, but you will not develop in short time better frontend framework than AngularJS, based on the fact that they have a dedicated team of engineers at Google. Use their framework, or chose another you like, but please do not create your own framework when you just need to deliver a product to your customers. 

### 2. Learn, learn, learn
"Anyone who stops learning is old, whether at twenty or eighty. Anyone who keeps learning stays young." (Henry Ford). 

If you really want to be a good software engineer you should be learning like crazy. Start getting used to learn one technology today and tomorrow learning one new technology because the first is already old fashioned: this happends in software engineering. However, the most important thing is to learn the basic concepts, the _essence_. Frameworks help us to ease our job, I really love them, but you should be asking the why, why the _black magic_ behind a particular framework works and how it was developed. 

I suggest that you look, for example, how Spring Framework implemented the DI mechanism in Java, how it works in Symfony with PHP, etc. I am pretty sure you will learn a lot from the source code. 

### 3. Find your motivation
Software engineering is one the fields in which the motivation of the people is crucial for building great software. As a software engineer and now, as a team lead, I really think that keeping people motivated is the key to succeed within a team. However, I consider that every software engineer should be finding his/her own motivation (technical challenges, new technologies, changes, good software practices, ...) and going for it. Your team lead / manager just will help you to achieve what really motivates you, so it is  very important that your team lead knows what motivates you and you plan with him/her how to achieve your goals.

### 4. Seek for code excellence
I know it is difficult sometimes, but you should be looking for the perfect code (like a surfer seeks for the perfect wave). Do not stop until you see that your code is _perfect_, paying too much attention to detail. The term _code excellence_ may be relative and it can depend a lot on the project requirements. However, broadly talking, I consider that a _cream code_ is the code that:

- Follows the coding standards / coventions of the team.
- Provides tests and has a minimun percentage of code coverage.
- Is documented and understandable.
- Is simple and modular (methods not having more than _X_ lines, computational complexity of functions should be less than _Y_, etc.)
 
In order to achieve this code excellence I suggest using [*Sonar*](http://www.sonarqube.org/), a web platform to manage code quality in your projects.

### 5. Test, test, test
Learn how to unit test and write testable and maintainable code. If you write good unit tests, you will ensure all edge cases are covered. Additionally, writing unit tests will force you to think about the solution you are designing and will lead you to implement a good software architecture (modular, extensible, maintainable, ...)

One frequent mistake I have seen in several projects is that people tend to think that testing code is not production code so it does not need to be quality code: it could be duplicated, no patterns are needed, non-performant, etc. *Big mistake!* all the code in your project needs to be quality code, otherwise you will suffer endless refactoring sessions in your tests.

[The art of unit testing](http://artofunittesting.com/) is a good book to learn what unit testing is all about.
