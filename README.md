# Ultra tiny LMS Challenge!
This is a technical challenge for hiring DEVs at Mobiliza.

First, some context: LMS stands for Learning Management System and it is basically a set of functionality to help Training Specialists (our case) and Teachers to provide curated content and track students interactions with them.

During this challenge, you will build an ultra tiny version of an LMS (Learning Management System). Here at Mobiliza, we use React, Node, Postgres, and Docker — and we’d like you to use this stack in your solution as well, since part of the evaluation is based on how you work with the technologies we use in our day-to-day.

## The app

It consists of a 3 screens flow.. The first is where the user should input their name/username:

![Diagram containing a username input.](https://github.com/mobiliza/ultra-tiny-lms-challenge/blob/main/assets/set-username-mockup.jpg?raw=true)

After submitting, she must answer the next question:

![Diagram a multiple choice question.](https://github.com/mobiliza/ultra-tiny-lms-challenge/blob/main/assets/question-mockup.jpg?raw=true)

**(Only #expertiseNaGestaoDeProjetos is wrong — the other four are right.)**

After submitting again, she should gain a score following this rules:

1. Selected all correct values and no wrong value: 100
2. Selected any wrong value: 0
3. Select half of the correct values: 50
4. Select a quarter of the correct values: 25
5. And so on...

Finally, she should see a screen with a ranking listing all of the answers ordered from highest to lowest with her own score highlighted. 
In case of ties, the oldest ones come first.

## Criteria

Since this is a Full-Stack challenge, we will be examining the logic, design, and user experience. We value code clarity and require that your submission includes unit tests to verify the functionality.

We expect a fully responsive solution and we want to evaluate your styling skills (CSS, styled-components, whatever) so if you're going to use a CSS library, customize it a bit.

It's important that we can run your application with instructions on how to run it.

After a successful submission we will invite you to a online chat in order to talk about your design choices and how you would develop specific new features on top of what you build. Please be ready.

## Submission

In order to submit this challenge, please create a private repository and share it with us (KZTN, betofigueiredo, tejota and andressafgd, RodolfoJr3564). We ask you not to make it public before July 2025. After that you should definitely make it public and add it to your portfolio.
