---
layout: post
title: "Spring Start Here: Chapter 1 notes"
subtitle: "my notes from chapter 1 of Laurentiu Spilca's book on Spring"
---

This first chapter mostly deals with what Spring is: the most used Java framework in the world today. 

A framework is defined by Spilca as a set of common functionalities that provide structure for creating applications. The idea here is that there is a lot of boilerplate involved in putting an application together, and using a framework saves you a ton of time by allowing you to focus on what makes your application unique rather than having to reinvent the wheel each time.

In this chapter Spilca explains the usefulness and vastness of the Spring framework with a good analogy. He asks the reader to imagine buying furniture from Ikea, except instead of getting the components for the piece of furniture you bought, you get _all_ components available. It's then up to you to select the pieces you need and assemble them correctly. Spring's usefulness stems from the fact that it supports a vast array of functionality, but the challenge comes from this vastness. Indeed, Spring is better thought of as an ecosystem of frameworks that share certain design concepts and standards and therefor play well together, rather than as a single framework.

The main components of this ecosystem are:

1. Spring core: Includes foundational capabilities. Particularly important here are the context and aspects. More on these in later chapters.
2. Spring Model, View, Controller (MVC): This allows you to create web apps that serve HTTP requests. 
3. Spring Data Access: provides you with the tools to connect to SQL databases. NB: Spring Data Access is a module of Spring Core and should not be confused with Spring Data which is an independent project in the Spring ecosystem. 
4. Spring Testing: provides testing capabilities.
5. Spring Boot: This is a project in the ecosystem that follows the principle of "convention over configuration". It allows you to quickly spin up an application with common default settings that you can then modify and refine as needed. 

Spring Core works according to the _inversion of control_ principle. This means that execution is not controlled by the app we write, but rather that the framework controls the app's components. This is possible by making such components visible to Spring. This is what the spring context does. 
The actual process of controlling the components is done by intercepting the methods of the app's instances (which are visible to spring through the context). This is called _aspecting_ and is another foundational capability of Spring Core.




