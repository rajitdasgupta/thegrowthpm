---
layout: post
title:  "10 Things You Need in Your Product Requirements Document"
description: "Learn how to write an easy-to-read product requirements document (PRD) that works for all stakeholders - with this simple ten-point checklist."
date:   2019-02-17 17:42:23 -0800
categories: product
permalink: "/:categories/ten-things-product-requirements-document"

---


# What makes a perfect Product Requirements Document (PRD)?

Just like a Product Manager, a PRD needs to perform many different roles simultaneously and effectively. It will be consumed by Designers, Marketers and Engineering teams and needs to communicate all the necessary information they need.

All you need to do -- is think about the end user, and pre-empt the questions they would ask.

Let's jump in.


## 1. Document meta data

![Product meta data](/images/product-meta-data.png){:class="img-responsive"}

Like any great book, a product requirements document should be timeless. If someone has a question about the feature you are building at any time -- this document should be easily searchable and scannable.

Say in 6 months, testers find a bug related to your product -- the developer in charge of this fix will need to get up to speed on intentions behind this feature, and the people involved (in case they have more questions).

This section can include **version number**, **contributing stakeholders**, **important dates**, and a **link URL of the epic/task**.


## 2. Background and motivation

This is the why behind your product. Be assertive, but brief - treat it like an elevator pitch. If possible, throw in some impact estimates like:  
  
> "this feature is expected to save 10 hours per month for the Operations team"  

OR  

> "...improve engagement rate by 30%" 
  	
If your stakeholders are spending a non-trivial number of hours working on this product - they need to know it's worth it.


## 3. Existing data and user-research



For more complex product - you'll want to include the data about the current state. If you are doing some user research in the pre-specs stage, you'll want to include a summary of this as well.

For example: if you are redesigning the checkout flow, describe the current payment funnel behaviour and the drop off rate at each step. If you have surveyed people who have abandoned cart - provide a brief of the main learnings.

## 4. User stories

A user story is a unit of development which can be independently estimated and serves a distinct need or purpose for your end user. You should be able to easily tell if a user story has been satisfied or not.

Break your high-level goal to its constituent stories and describe the implementation logic briefly. Assign priorities to each. Be more detailed with high priority stories. If task tickets have been created, link to these here.

## 5. Design specifications

This is most crucial part of your product requirements document -- which your developers will spend the most time on.

Map out the user flow (I'm a huge fan of [draw.io](www.draw.io)) and include mockups for screens if you think that is valuable. Link to high fidelity mockups where applicable.  

## 6. Feasibility assumptions and known edge cases

The hallmark of a great PM is the ability to pre-empt questions from their stakeholders. This helps reduce the back and forth between teams and move the product implementation along.

Mention the assumptions you have made about user (and system) behaviour while writing the specs and what the intended behaviour should be when certain edge cases are encountered.

For example: you might choose to implement a payment flow where a user does not have to create an account before making a payment - but rather just entering their email. The underlying assumption is that users will not intentionally make a payment using an unknown person's email address. If a user erroneusly enters the wrong email and makes a payment -- the operations team will redress this manually. 

## 7. Data storage and third party integrations

When users interact with your feature, describe how you want this information to be stored - whether that's in your own database or in a third party tool. In many organizations, this is handled by developers - in which case, work with them to add this in. 
  
As a PM - even if you're not doing this yourself, it is beneficial to know how this data is stored so you can track the performance of this feature later.

## 8. Acceptance criteria

These are the conditions that the product needs to satisfy in order to be accepted by the user (this can be a customer, internal team member, or system - if you are working on a system level feature). This is critical for developers and QA engineers - since they will be using this to write test cases.  
  
Well written acceptance criteria should be:  
* Simple to read, with a clear definition of "doneness" (pardon the cooking analogy) 
* Written before development work begins, so that the customer intent is not diluted by the realities of development 
* Focused on the WHAT - not the HOW. It should describe the intent and not the solution

## 9. Success metrics and measurement

Focus on one primary metric that you are looking to improve with your feature. For example, if you are redesigning your checkout page - you should track your payment funnel conversion rate.

You can mention other secondary metrics that might be affected by your changes - e.g. time on page, average order value etc. - but these are not critical.

Mention how you plan to track these metrics - even if you don't paste in the actual queries and dashboard links, this will save you some time when you follow up with the team about the success/failure of the feature.

## 10. Negative scope

Just as you need to be clear about the features you want to implement, you need to be equally clear about the what is out of scope. 

This is another area where you should anticipate questions beforehand and clarify these as early as possible. This reduces back and forth during the review and development process, and keeps the team's eye on the ball.
