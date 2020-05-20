# OpenCookerProject

## What is this?

This is an idea that I have had for more than 10 years. And because I think about it almost every day I have created this repository to collect my thoughts and ideas. The plan is to create a machine that will cook a meal for you in the same way that a dishwasher does your dishes. I imagine it to be about the same size. 

## Wouldn't it be easier to buy a microwave meal or order takeout? Can't you learn how to cook?
I know how to cook a meal! It is just that in my mind there are two types of cooking. The this-is-gonna-be-great kind that you do on weekends and the Im-hungry-feed-me kind that you do on weekdays. Just like there are multiple types of driving; one where you drive to work in the rain on a Tuesday morning and one where you drive a convertible down curvy mountain roads. You need different equipment for it. Something comfortable, reliable and cheap to get you to work. And an rear wheel drive convertible with a manual gearbox for the weekends. This machine is for the weekday cooking. 

## So how does this thing work?
It is the size of a dishwasher and it is part freezer and part cooking machinery. You fill it with measured frozen blocks of ingredients and the machinery preprares a meal from it. It could have a pan to cook things like pasta and vegetables. A frying pan to fry things and combine things. And some way to transfer the finished result from one pan to another. Like add the pasta and the vegetables to the pasta sauce and the (mock) meat. When the meal is finished it will clean itself internally.

## What about recipies?
My current job is to write recipies in Ansible, they are for servers not for food. Most food recipies seem overly complex and also simplified to me. There is no structure, no checks, no modules and most are very vague. I recently learned about BPMN from a client (thank you!) and that seems like the perfect way to implement recipies in a system. Ansible seemed like a good start but this is more flexible and more user friendly. Tools like Camunda store BPMN in .xml-files which can be stored in Git. And then people can collaborate and really share and improve recipies. Recipies will be so much better!

## Recipe modules and recipies with requirements and dependencies
To me a recipe is the combination of modules and partial products. Before the machine starts it checks if it meets all the requirements. If it has enough ingredients and if it has the right internal devices to complete the process. If a step requires baking and there is no oven module installed there is no point in even starting. Realizing that I have forgotten to buy or eaten an ingredient has happend to me too often. Modules could be making a sauce, side salad or just potatoes. 

## Why the frozen ingredients?
For a couple of reasons actually. The first being to prevent spoiling and food thus waste. Frozen vegetables are just as healty as fresh ones. Frozen ingredients are also cheaper to transport because the take up less size and don't spoil in the process. Less waste on the producers side and less waste in your kitchen. Because the food is stored in the machine and not in your fridge you can check if you have the right ingredients for a recipe from your phone. And maybe have the machine order ingredients when you are about to run out. It is also fine if you don't use the machine very often. Water should not be frozen, it should be connected to tap water and have an exit for waste. Just like a dishwasher. The ingredients should be natural and not preproduced. For example broccoli, salt, pepper, tomatoes. But not something like pasta sauce. Pasta sauce should be a module that can create a fresh sauce from the tomatoes.

## Are you actually going to build this, do you have relevant experience?
I want to start slowly and I am collecting skills and information. I'm also getting to know people that may be interested and want to help. I have worked for a startup that made 3D-printers so I have some knowledge of the process of building a machine. I can code and manage servers. And I can cook. Hehe. 
The first steps could be some drawings, some very simple recipies and maybe a list of features that a minimal viable product should have. 

## Collaboration
I haven't really started but I would like to hear ideas. Feel free to contact me, open a pull request or start by yourself.
