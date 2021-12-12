+++
author = "Blitzerr"
title = "correct systems: A Proposal"
date = "2021-11-21"
description = "My musings on implementing correct systems"
image = "systems.png"

draft = true

tags = [

    "distributed-systems",
    "verification",
    "thoughts"

]

+++

# Settings the Stage

In my last post we discussed the Iron fleet. I strted off there as a lot of what I want to talk about here is inspired by the [iron fleet](https://www.microsoft.com/en-us/research/wp-content/uploads/2015/10/ironfleet.pdf) paper. I have been thinking about verifiably correct system implementation lately. This is imporant because an incorrect system evades the trust of its users and as designers it's not gratifying to have built a system that fails spectacularly. For business, it means spending time and money in fixing bugs when that effort could have been spent in adding more value to the system. So, how do we begin writing such a system ?

Iron Fleet says do it in steps or layers of abstraction. This is a powerful idea and is used extensively in engineering. What are the right layers of abstractions one must ask ? There is no fixed answer to it. Usually, we all must start at the spec layer and end at the implementation layer but the layers in between are left to the system designer. Somewhere in between the two layers, it is a good idea to have the crutial layer that cuts over the abstraction of the system as whole and the system as a composition of discrete and independent hosts. 

## Spec

A spec is a concise description of the system. This is something you can give to a savvy user and they would know the capabilities of the system. Therefore, the spec should be user centric. So, then the natural question is what do the user wants. 

Based on my experience, users care about three things:

1. What is the system capable of ?
   This usually boils down to the actions that can be performed on the system. The other definition is the API surface area of the system.
2. The promises from the system ?
   This is usually about the system invariants, or that's how the spec models it. 
3. Cost of running the system.
   We won't talk about that here. But people care about it and they would like some way to keep tabs on their monthly bill.

The Spec should provide the answer to the points 1 and 2 in addition to something else, that your users may not ask of you directly but if you have it, it gives them more faith in your system, which is a mecahnical proof that the invariants hold for all possible actions on the system.



Well, one thing I can tell you that none of your users what to spend time thinking about the inner workings of the system. They don't want to decide the number of shards or nodes in the system, what instance type to select and preferably, not even the schema for the data they are going to save in it. I am eluding to a storage system but the same principles apply for a compute system as well. Ideally, users want to just tell you what they would like

#
