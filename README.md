# demo-commerce

Demo commerce is an opinionated e-commerce solution implemented with event-driven microservices. 

This project serves eduactional purposes only. None of the featured microservices is meant to be used in a production environment. The main point here is for me to have some fun while trying out "eventstorming-like" modeling and applying DDD.

This concrete repository contains only description of some of the problems which a fictious online shop would be dealing with. The individual microservies mentioned in the context map are available in separate repositories. Each of them is purposfully developed in a different style with the goal to explore a given subdomain or a solution to a technical problem. For example the [shopping-service](https://github.com/gkosharovdev/axon-kafka-spring-boot) (ft. a checkout process) is showcasing the Eventsourcing+CQRS patterns with the help of the Axon framework.

## Domain model

The approach to go from problem space to solution space is loosely following the guidelines from [Alberto Brandolini's book](https://www.eventstorming.com/book). I find it cool because it encourages people to think from the perspective of the actors interacting with the system. Always having in mind their experience is bound to produce a useful model.
Here are the 3 steps:
1. Create a "Big picture" featuring the most relevant processes along with respective actors
2. Transform into a "Design level" artefact wich contains the bare minimum (e.g Events, Aggregates, Policies, etc.) necessary to reason about the implemnetaion
3. Code a bit, see if it sticks and iterate over the big picture and the design

This last step 3 may seem a bit vague but I think it's important to set up a feedback loop between implementation and design because more often than not logical flows tend to surfice while coding.

Miro is the tool of choice for this project.

### Big picture



### Context map



### Design level
