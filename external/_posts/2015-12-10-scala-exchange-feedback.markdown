---
layout: post
title:  Scala exchange 2015
date:   2015-12-10 10:00:00
author: Nilesh Gupta
categories: conferences scala
image: /images/blogs/scala-exchange-2015.png
excerpt: Sky sponsored Scala exchange 2015 . It took place in London on 10th and 11th December.
---


This year first time Sky sponsored Scala exchange . It took place in London on 10th and 11th December.

I have attended [Scala exchange in London](https://skillsmatter.com/conferences/6862-scala-exchange-2015) which was very good experience .
It was excellent get together of techies keen on scala . Everyone had chance to discuss with experts ,
also to interact with organisations developing systems using scala and hiring details ,
attending various talks and workshops . Sky was one of sponsors for the event and we had our booth. It had static cloud of scala and related technologies  .
We had excellent raspberry pi game build on scala ,akka and angular JS front end .Participant compete for NOW TV box by scoring on reaction time by clicking on button that led in raspberry Pi suggests.
Also there was board which displays four main Scala systems in Sky and all technology stack used in various projects .
We also had very tasty cup cake with Scala , Sky and Akka on it

## Docker


Exchange had many good talks and one of them was on Docker by [Mario](https://skillsmatter.com/members/thedoc) .
    It was mainly on how to take advantage of Docker containers to ease development,
    testing and deployment of Scala applications, especially those that are based on Akka.
    He talked about basic concepts of docker which includes docker machine , docker client , container, images and registry.

what I took away  ?  It is excellent way to change the notion that ‘It works locally on my machine’ .
    Complex build setup again and again on various environment won’t be needed .
    Creating configuration to the setup environment and dependency only once.
    This will be save a lot of effort for environment setup in development , testing and deploying to production .
    Thou it would be very interesting to see , it working in production .
    Mario claims it should make little difference in performance while running in container as it doesn't need separate kernel .

what I’d do differently after this talk ? Implement docker files for project which can be configured for various environment
    and push version controlled image created to central repository/registry . And once you have docker on machine ,
    you just need to download the image from repository and start the container which has all setup for environment
    to run . You can run as many container as you like in a machine , Just need different port for container on same
    machine or different docker-machine .


  [Understanding Architecture of Docker](https://docs.docker.com/engine/introduction/understanding-docker).
  
  [Docker talk by Mario during scala-exchange](https://skillsmatter.com/skillscasts/6987-scala-and-akka-and-docker-oh-my#video).
