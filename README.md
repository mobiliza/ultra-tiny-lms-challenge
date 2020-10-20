# Ultra tiny LMS Challenge!
This is a technical challenge for hiring DEVs at Mobiliza.

First, some context: LMS stands for Learning Management System and it is basically a set of functionality to help Training Specialists (our case) and Teachers to provide curated content and track students interactions with them.

During this challenge you will build an ultra tiny version of an LMS. We use React, Node and Postgres here, but you can use whatever technology you want.

## The app

It consists of a 3 screens flow.. The first is where the user should input their name/username:

![Diagram containing a username input.](https://github.com/mobiliza/ultra-tiny-lms-challenge/blob/main/assets/set-username-mockup.jpg?raw=true)

After submitting, she must answer the next question:

![Diagram a multiple choice question.](https://github.com/mobiliza/ultra-tiny-lms-challenge/blob/main/assets/question-mockup.jpg?raw=true)

After submitting again, she should gain a score following this rules:

1. Selected all correct values and no wrong value: 100
2. Selected any wrong value: 0
3. Select half of the correct values: 50
4. Select a quarter of the correct values: 25
5. And so on...

Finally, she should see a screen with a ranking listing all of the answers ordered from highest to lowest with her own score highlighted. 
In case of ties, the oldest ones come first.

## Criteria

Since this is a Full-Stack challenge, we will be examinating the logic as well as its design and user experience. We value code clarity, so careful naming and unit tests will give you some points.

We expect a fully responsive solution and we want to evaluate your styling skills (CSS, styled-components, whatever) so if you're going to use a CSS library, customize it a bit.

It's important that we can run your application so please provide a Readme.md with instruction on how to run and/or deploy it for free somewhere (Bonus points for that).

After a successful submission we will invite you to a online chat in order to talk about your design choices and how you would develop specific new features on top of what you build. Please be ready.

## Submission

In order to submit this challenge, please create a private repository and share it with us (pedromuller, tiago-peixoto). We ask you not to make it public before April 19/2021, which is exactly 6 months after this challenge was created. After that you should definitely make it public and add it to your portfolio.
