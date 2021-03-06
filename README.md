# BuildAR

## Inspiration
As millennials, we are quite blessed to be born in an era where anything is possible with technology. Nowadays, it's quite normal for consumers to buy groceries online, doctors to consult machine learning models for predictive analysis, and for people to have surreal experiences unlocked with VR/AR technology. However, with change comes...well...more change. Many of us have been so obsessed with technology, that we have lost basic life skills needed for survival. For example, not knowing how to do laundry, navigate in a foreign country, flirt with girls, and most importantly, build furniture. Luckily, BuildAR knows this, and gives a beautiful AR solution to the issue at hand.

## What it does
BuildAR simulates the process of building furniture, step-by-step. Users can follow along with the instructions provided, which ensures a seamless, and flawless process with real-time visualizations. Additionally, BuildAR will send an SMS when the user is stuck on a certain step, providing resources with extra information on the specific step.

## How we built it
BuildAR leverages Android's ARCore to provide the augmented reality visualizations. Regarding the back-end service, stdlib's services were heavily used. Stdlib's bread and butter, turning modular functions to scalable API endpoints, was used to provide BuildAR's back-end API, which interfaces with MongoDB. The scheduled tasks functionality and MessageBird API were used to provide SMS texting to the user.

## Challenges we ran into
One of the prominent issues our group had to face in the beginning was practicality versus perfection. We spent the entire first night debating ideas, attempting to find the "perfect" idea. We soon realized that simply creating the plan of execution would be worthless if we didn't have enough time to implement the idea itself. Reluctantly, we went with the idea of BuildAR, which we weren't sold on 100%, because more time wasted on planning meant less time for hacking. Moreover, many of us are full stack web developers, so we were definitely put out of our element when working with mobile development, AR development, and design.

## What we learned
The biggest takeaway, that all members will leave HackPrinceton with, is the lesson of balancing a plan of execution, and the execution itself. The problem we faced at HackPrinceton is the very reason why Agile is very popular amongst tech companies today. Create a presentable MVP that works, and continuing improving and pivoting throughout the journey of the product.

## What's next for BuildAR
What's next for BuildAR is PlannAR. PlannAR is the concept where room customizations along with the AR visualizations are combined together. Users will input the budget they have set for their new room, and PlannAR will delegate the set budget on the items the user requires. Because of the time constraints of the hackathon and lost time from debating over project ideas for the first night, we did not have enough time to pivot into said planner app. But stay tuned...for PlannAR!

## Check us out on Devpost!
https://devpost.com/software/aroom
