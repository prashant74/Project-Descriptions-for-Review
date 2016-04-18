#[DevOps P0] Improvement Plan: Sample Submission

## Introduction

This is a sample submission for the Improvement Plan project. Use this as a guide as you create your own submission based on either your own situation, or the fictional company described elsewhere in the project materials.

Notice that the submission includes a date for each answer. As you progress through the Nanodegree program, you will be invited to return to your Improvement Plan and to update it based on the new skills and techniques you have acquired. Please **leave in your previous responses** to each answer, and add a new one below with the date. This will make the project a living document that will serve as your own record of what you have learned.

## Organizational Snapshot

#### What is the core function of your team? What is the core function of your company or organizational unit? Is the core function of your team well aligned with the function of the larger organizational unit or the company as a whole?

**April 13**

* Team goal: Provide an online shoe store for customers
* Company goal: sell customers shoes

#### Who are your team's customers? Are they internal or external? What do they need?

**April 13**

* External customer: users of the online store. They need to be able to buy shoes.
* Internal customer: Accounting team. Need to receive daily totals of online purchase receipts.
* Internal customer: Warehouse team. Need to receive details of each transaction including exact shoe model, size, and color sold, and also shipping address so the shoes can be sent to the purchaser.
* Internal customer: Purchasing team needs summary report of shoe styles sold each week for forecasting and restocking purposes.

#### What is the current flow of software development and delivery in your team? List the main steps and whether they are manual or automated. 

**April 13**

* Feature requests, bug reports, etc. are checked every Monday and project manager determines priorities for the week (manual)
* Code gets written based on priorities (manual)
* Software gets checked into codebase (manual)
* Every Friday afternoon it gets deployed to a test server (manual) 
* QA team tests it and files bug reports or signs off as appropriate (manual) 
* Once a month codebase is sent to ops team for deployment into production (I don't know if it's automated or manual, but judging from ops usually staying late for the release days it's manual).

#### What are all the teams or people that are involved in a product release, from start to finish? 

**April 13**

* Project manager
* Marketing
* Design 
* Developers (my team)
* Testers, QA
* Ops

#### How is communication handled in your organization? 

**April 13**

We pretty much just talk within a team and with a manager and PM. I sometimes talk with other teams over lunch and usually find out a lot of interesting things that are even helpful at work.

# Quantitative Ratings

#### How satisfied are you with how other teams work and support the work that you do? (Scale: 1-10, 10 is best)

**April 13**

Now - 6. 

#### Do deployments go smoothly? (Scale: 1-10, 10 is best)

**April 13**

Now - 3. We had major problems the last couple of times with code not running properly in production though it was fine in testing. E.g., Customers were not able to click the checkout button.

#### Do you have planned downtime for system upgrades or maintenance? 

**April 13**

Yes, usually once every 1-2 months in the night.

#### How much time does it take to set up the environment for a new project? 

**April 13**

About 2 days, if sysadmins are not busy with release or a week if they are busy.

#### How often do you deploy to production? 

**April 13**

Now - 1/month
Ideal - maybe 2-3/week

#### How long does it take to deploy a new feature or bugfix from "code checked in to repository" to "feature is live to customers"? 

**April 13**

1-3 weeks

#### How easy is it to deploy a new feature or bugfix from "code checked in to repository" to "feature is live to customers"? (Scale: 1-10, 10 is best) 

**April 13**

Now - 3. It takes too long sometimes, even when the bug fix is done, to get on to the production servers because they have to be shut down and brought back up which is not acceptable for sales. 

#### How would you rate the quality of your software? (Scale: 1-10, 10 is best) 

**April 13**

Maybe 6. It's ok. We have a testing team with a good routine and a bugtracker with good rules for dealing with issues.

#### How easy it is to test your software? (Scale: 1-10, 10 is best)

**April 13**

Now - 5. The testing team is good about the routines but sometimes even when everything works in testing it is broken in production.


#### How satisfied are your customers? (Scale: 1-10, 10 is best)

**April 13**

Around 7. They are okay. We have a feedback link on our site, and we follow what people say about us in social media.

## Conclusion

That's it for the sample submission! Something like this would meet specifications for the project. However, the sample represents a typical effort, not the best. For instance, the sample does not provide any insight into steps that might be taken to remediate the problems in the software development lifecycle. The goal of the project is to get you started thinking like a DevOps Engineer, so the more concrete details you can give about problems and possible solutions, the better.

[Back to Project Description](P0_Improvement_Plan.md)

[Project Submission Template](P0_Template.md)