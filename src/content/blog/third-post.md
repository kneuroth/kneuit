---
title: ""
description: "Business value VS developer sanity Corpo"
pubDate: "Jul 22 2022"
heroImage: "../../assets/blog-placeholder-2.jpg"
---

MVP iteration is useful way of building software, especially when providing value is keeping your team afloat. If you're in a team that relies heavily on the skateboard -> bicycle -> motorcycle -> car analogy, then you may have experienced some frustration with this model. You finish a sprint cycle with a perfectly running shiny new car, but turning around and hearing a stakeholder ask for a convertable next, and finding that you'll have to either duplicate 95% of your code for this new convertable effort, or re-write your entire repository to allow for retractible roofs (rooves?). Whether you've been in this situation or not, it's helpful to keep an adjacent, but more future-proof iterative design methodology in mind, which is to think car -> car factory -> car factory blueprint. If you feel that whatever feature or product you're building could be providing value in other areas with just a few tweaks, then start to think more on abstraction than value add at each stage of development.

(example)
The abstraction can only come only come out after the first version. Pay attention to business asks and the why behind the work. You might need to be building a framework.

(why this was messy)

(takeaway)
Takeaway: If you're noticing that you might have to solve similar problems later, priority clarity of code (because youll be revisiting and reusing) over cleverness. Isolation of functions over hypergeneralization - it's often easier to write implementations of classes than to create 1 class that covers all situations. Provision space to grow.

(payoff)
Payoff: You end up being able to create your first version with a simple config file or declared object.
You can make as many cars as you want
You arent doing tiny code tweaks, pushes the work to the business to setup their value adding machine themselves.
