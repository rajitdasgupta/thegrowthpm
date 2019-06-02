---
layout: post
title:  "4 Tools To Supercharge Your Marketing Stack"
description: "Remove tech and design dependencies by using these tools - so that you can make quicker marketing iterations."
date:   2019-06-01 17:42:23 -0800
categories: marketing
permalink: "/:categories/ten-things-product-requirements-document"

---

Experts like Sean Ellis say that a growth team's success depends on their ability to iterate rapidly through conversion rate experiments, channels and funnels. The learnings compound on each other to move the north-star metric of the business.

Easier said than done, right? In my marketing career, I've run into this a lot.

Designers and developers at startups will be pulled in many different directions. As a marketer, you're competing with the rest of the organization for their time. But what if the ask is as simple as adding a line of Javascript to your webpages?

I'm sure you're asking yourself if there's a better way. 

There is.

In this post, I'll dive into a few tools that I use daily to make marketing iterations quicker, and more effective. This way, your design and tech teams can focus their energies on more impactful projects.


# 1. Google Tag Manager

![google tag manager](https://i.imgur.com/831Wyb0.png "google tag manager")

In a fast growing marketing team, you are constantly trying out different tools to augment your stack. Most of these work by inserting some javascript code into your HTML templates. Some examples include:
1. [Intercom](https://www.intercom.com/) (on page chat)
2. [Hellobar](https://www.hellobar.com#ref=rajitdasgupta) (hovering CTAs and popups)
3. [Adroll](https://www.adroll.com/) (display retargeting)

Next, you'll want to know how users behave on your platform. Analytics tools work much the same way, since most user behaviour is tracked on the front-end. Hotjar (tracks user engagement on a page). Google Analytics/Amplitude/Mixpanel, Segment are mainstays on most marketing stacks these days.

Finally, each ad platform you spend on will need some mechanism to track conversions. Facebook, Adwords, Reddit, Quora -- all these use similar tech to track conversions and ROI.

Having been in the growth business for some time now, I can assure you that you'll grow into (and out of) these tools faster than you expect.

Google Tag Manager (GTM) lets you manage these scripts and the data that they send with full control - all in one interface, without implementing a single line of code. 

They also have a neat feature that lets you roll-back to previous versions in case some change breaks your website.


# 2. Zapier

![zapier](https://cdn.zapier.com/storage/photos/da37bf1ea282413139a57c1c911e7c4b_2.png "zapier integration")

At startups, it's common to have your stack spread across tens of different marketing tools. Zapier is a way for them to talk to each other. You can set up workflows - each having a trigger and a corresponding action. With 1000+ apps supported, Zapier leaves most of its competitors like Automate.io, and actiondesk in the dust.

Some examples of automation that I've used:

1. Sending sales reps a Slack notification when a lead pays for a product.
2. Sending information about new leads to a google sheet so that sales reps can follow up via phone.
3. Save incoming Gmail attachments to Dropbox

Mind you, all these neat superpowers come at a cost - beyond 100 tasks, Zapier will set you back $18/month. If you're in the market for a free tool, check out IFTTT. It manages to pack a punch - though lacking much of the configurability that Zapier provides.

# 3. Unbounce

![unbounce](https://i.imgur.com/dqxtXKi.png "unbounce")

Landing pages can take anywhere between 2-4 weeks to go from wireframes to the final product on your website. This is a lifetime in a marketers world. So the next time you are creating a new landing pages, ask yourself a few questions.

-- does this page have any intrinsic SEO value, or can it live independent of my website, without being indexed by search engines?
-- will I need to make frequent edits to the page?

If you answer to both is yes, consider a landing page builder.

Paid marketing campaigns need you to iterate quickly on your landing pages so that you are collecting the most leads for your ad spend. In this situation, you can't afford long design and development cycles.

A landing page builder like Unbounce will help you run a lean ship. Other alternatives include Instapage, Leadpages and Clickfunnels. The only downside is that these landing pages will need to live on a subdomain. You'll need to tweak you DNS settings to map this subdomain to Unbounce.

All these tools have a library of high-performing templates to choose from. Given that these companies store conversion data for millions of landing pages, these templates will start you off from a good baseline.

If you're a stickler for design and branding consistency, you can ask your designer to create a one-time page template that's on brand.You can then duplicate and tweak this for other paid marketing campaigns.

Some alternatives: Leadpages and Instapage

# 4. Visual Website Optimizer

![VWO](https://wingify.com/images/product_screenshot@2x.png "VWO")

Once you have defined user flows on your website for lead generation or payment conversion, you need to survey your users and show them messaging that will minimize any friction that prevents them from converting.

VWO gives you the tools to survey your users, record your hypotheses, and set them up as A/B tests on your website. Now you can validate whether they lead to higher conversions.

Some A/B tests that I've implemented in the past:

1. Static hero banner image vs. a video
2. Lead generation form at the start of the page vs. at the end
3. Showing monthly price vs annual price

Tools like Unbounce let you implement A/B tests as well, but the functionality is somewhat limited.

If you are just starting out and looking for a free alternative, check out Google Optimize. On the other hand if you have a sophisticated testing culture and can shell out the extra $$, you can look to Optimizely.

# A warning about using Javascript based tools:

1. Google Tag Manager (and any scripts you add with it) and VWO can increase your site load time. Most crucially, the time it takes for the user to start interacting with your pages. Intercom for one, is known for being a resource hog. So use these judiciously and remember to remove unnecessary scripts if you are not using them.
 
2. Adblockers and secure browsers (like Brave) might affect the firing of these scripts, so be mindful of the percentage of your visitors who use these. If you're a regular e-commerce company, this might not affect you - but if you are selling software to cybersecurity professionals, these tools would be useless.