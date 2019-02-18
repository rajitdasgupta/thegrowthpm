---
layout: post
title:  "10 Things You Need in Your Product Requirements Document"
date:   2019-02-17 17:42:23 -0800
categories: product
permalink: "/:categories/ten-things-product-requirements-document"

---


# What makes a perfect Product Requirements Document (PRD)?

Just like a Product Manager, a PRD needs to perform many different roles simultaneously and effectively. It will be consumed by Designers, Marketers and Engineering teams and needs to communicate all the necessary information they need.

All you need to do -- is think about the end user, and pre-empt the questions they would ask.

Let's jump in.


## 1. Product meta data

![Product meta data](/images/product-meta-data.png){:class="img-responsive"}

This includes **version number**, **contributing stakeholders**, **date**, and a **link to the epic/task**. 

Most of this is for cataloguing purposes, and is useful for those searching for context about this release months/years down the line.


## 2. Background and motivation

This is the why behind your product. Be assertive, but brief - treat it like an elevator pitch. If possible, throw in some impact estimates like:  
  
> "this feature is expected to save 10 hours per month for the Operations team"  

OR  

> "...improve engagement rate by 30%" 
  	
If your stakeholders are spending a non-trivial number of hours working on this product - they need to know it's worth it.


## 3. Existing data and user-research

For more complex product - you'll want to include the data about the current state. If you are doing some user-research in the pre-specs stage, you'll want to include a summary of this as well.

For example: if you are redesigning the checkout flow, describe the current payment funnel behaviour and the drop off rate at each step. If you have surveyed people who have abandoned cart - provide a brief of the main learnings.

## 4. User stories

Break your implementation to it's constituent features and describe the logic. Assign priorities to each. Be more detailed with high priority stories. If tech tickets have been created, link to these here.

## 5. Design specs

Map out the user flow (I'm a huge fan of [draw.io](www.draw.io)) and the designs for each screen. Link to high fidelity mockups where applicable.  

## 6. Feasibility assumptions and known edge cases

Mention the assumptions you have made about user behaviour while writing the specs and what the intended behaviour should be when the associated edge cases are encountered.

## 7. Data storage and third party integrations

When users interact with your feature, describe how you want this information to be stored - whether that's in your own database or in a third party tool. In many organizations, this is handled by developers - in which case work with them to add this in. 
  
As a PM - even if you're not doing this yourself, it pays to know how this data is stored so you can track the performance of this feature later.

## 8. Acceptance criteria

These are the conditions that the product needs to satisfy in order to be accepted by the user (this can be a customer, internal team member, or system - if you are working on a system level feature). This is critical for developers and QA engineers - since they will be using this to write test cases.  
  
Well written acceptance criteria should be:  
* Simple to read, with a clear definition of "doneness" (pardon my English) 
* Written before development work begins, so that the customer intent is not diluted by the realities of development. 
* Focused on the WHAT - not the HOW. It should describe the intent and not the solution.

## 9. Success metrics and measurement

Focus on one primary metric that you are looking to improve with your feature. For example, if you are redesigning your checkout page - you'll want to track your payment funnel conversion rate.

You can mention other secondary metrics that might be affected by your changes - e.g. time on page, average order value etc. - but these are not critical.

Mention how you plan to track these metrics - even if you don't paste in actual queries and dashboard links, this will save you some time when you follow up with the team about the success/failure of the feature.

## 10. Negative scope

Just as you need to be clear about the features you want to implement, you need to be equally clear about the what is clearly out of scope. 

Anticipate queations beforehand and clarify these as early as possible. This reduces back and forth during the review and development process, and keeps the team's eye on the ball.
