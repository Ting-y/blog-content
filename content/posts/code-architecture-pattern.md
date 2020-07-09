---
title: "Code architecture pattern"
date: 2020-07-05T00:07:01-04:00
draft: false
categories: architecture
---

A pattern to all? In the article, I would like share how to use the same coding pattern/project structure to increase programming productivity, and flatten the learning curve when developer need to modify an unfamiliar code project.
<!--more-->


###  Why
In a microservice system, it's common to see different service is using different programming language. ex, Service A is in Python, Service B is written in Go. If a developer need to modify Service A, and he/she's primary language is Go, it will required some ramp up time for putting hands on keyboard. In my experience, the most time consuming is to understand the coding pattern and folder structure, so i can know what file need to change, and the rest is ***Learn X in Y*** [^1]

### How
Following example will show
- 2 different programming languages(Python & Go)
- Same pattern (Dependency Injection)
- Same folder structure (Clean code architecture from uncle BOB[^2])


### Example


![Onion Architecture](https://blog.cleancoder.com/uncle-bob/images/2012-08-13-the-clean-architecture/CleanArchitecture.jpg)
### Ending
Happy coding, and this is very helpful when your python teammate quit the job :smile:

### References
[^1]: https://learnxinyminutes.com
[^2]: https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html