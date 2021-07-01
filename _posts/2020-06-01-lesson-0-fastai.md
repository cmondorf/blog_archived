---
layout: post
title: Thoughts on _Lesson 0: How to fast.ai_
subtitle: The lecture before the first lecture
---

Recently, a new lesson was added to the fast.ai course. This lesson wasn't added to the end of the lessons already posted, but instead is meant to be seen before the current set of published lessons. In this post I highlight a few key points that struck me as particularly important and noteworthy.

## 1. Teach the whole game

Fast.ai is many things. It's a library that runs on top of Pytorch and makes it much easier to work with, it's a book on deep learning, a course, and even an approach to learning and teaching. What makes it special is that the people behind the course have put a lot of thought into their teaching methodology and have an explicit goal of breaking down barriers and making deep learning accessible. 

What sets this course apart from other more traditional courses is that it embraces a top-down approach to teaching. This philosophy was pionered by David Perkins, a professor of education at Harvard. He lays out his approach to teaching here:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/JRQY01Hhrww/0.jpg)](https://www.youtube.com/watch?v=JRQY01Hhrww)

The main idea is that you should teach "the whole game". He describes the example of teaching baseball. You don't initially teach people about aerodynamics, the physics of acceleration and friction which act on the ball, the psychology of team sports, the architecture of fields, etc. Instead you explain enough for them to start playing. Then, with practice they iteratively improve over time.

Perkins has distilled his approach to teaching through the following 7 principles:

1. Play the whole game. You may need to start with junior versions. You learn to ride a bicycle by actually riding a bicycle, but maybe don't start on the _Tour de France_.
2. Make the game worth playing. Excitement and curiousity can be powerful allies on the journey to learn something.
3. Work on the hard parts. He talks about "zooming into the challenging bits".  This can help you perfect some technique or practice an essential move. 
4. Play out of town. Transfer is a tricky part of the learning game. I once read about a study of street children in Brazil who were able to perform complex computations in their head, but were totally unable to apply math skills in any other domain. Being able to take your skills with you is the mark of truely having internalized them.
5. Reveal the hidden game. In the case of baseball this would be strategy. I'm guessing in other domains this would be things like implicit knowledge. In learning theory explicit knowledge is what is written down in textbooks (chemical proceedures, for example) and implicit knowledge is stuff that isn't written anywhere but is important (such as lab etiquette, perhaps).
6. Learn from the team. Make it social. As the saying goes "if you want to go fast, go alone, but if you want to go far go together."
7. Learn the game of learning. This is important. We ignore metacognition at our peril. You see this all the time with language learning apps and courses that can't possibly teach anyone a language. Often what sells these courses is the illusion of learning as opposed to actual results.

## 2. Finish the damn course, and build things from the very beginning

Here, Jeremy Howard mentions Radek Osmulski as an example both of what not to do, and what to do. Basically, we should avoid Radek's initial approach which was to try to learn all the basics and fundamentals before building anything, and learn from his successful second run where he put building and coding front and center. By his own estimate, the winning fomula is 60% doing, 40% learning. 
Radek has written an entire book about what he learned about learning fast.ai and deep learning generally. I've read the book and will write a review of it soon, so I won't go further into it here.

The main point to take home here is that, as Jeremy puts it "reading books and watching tutorials won't get you there." You'll learn by doing, in the same way you won't learn to ride a bike by reading about how to ride a bike. You'll learn by getting on the bike (and falling!).

## 3. Address things that you're missing

Here again Jeremy quotes Radek. Radek has written that mastering DL  relies on a four-legged table. The legs of the table are:

1. code concepts
2. mastering an IDE
3. mastering Git and GitHub
4. learning about ssh and linux to be able to use remote servers

Of course, this raises the question of how to learn these things. A good place to start seems to be [The Missing Semester](https://missing.csail.mit.edu/). This is an MIT course that is available on youtube that covers these missing topics. I haven't worked through this course but intend to and will write a review when I've finished it.

## 5. How to go through a fast.ai lesson

Both Jeremy and Radek mention four steps to go through when approaching a fast.ai lesson:

1. watch the lecture
2. run the notebook, experiment!
3. reproduce results
4. repeat with a different dataset

This time around I haven't been watching the lectures, though I intend to pick them up again. Instead, I've been participating in Weight's and Biases' [reading group](https://wandb.ai/wandb_fc/events/reports/Welcome-to-the-Fastbook-Reading-Session---Vmlldzo3Mjk0Mjg?galleryTag=fastbook). This has been a great experience as there's a great social component there (the team Perkins talks about).

However, I've been reading the book and then using the notebooks that correspond to each chapter. The nice thing is the entire book is available on github as runnable notebooks. Not only that, but they're there in two versions. One is the book as it's published, but the other is a set of 'clean' notebooks, that is to say notebooks with the code but no prose. Running the latter while reminding myself of the content of the prose is a great way to review.

Another important piece of advice Jeremy gives is that when approaching a project generally, not just those mentioned in the book and course, you should aim to build a very basic end to end process that builds or processes a dataset, prepares the data, trains a model and makes inferences. This first iteration will probably not be very good, but it will allow you to solve challenges linked to setting up the end to end pipeline. With that ready it's much easier to iterate and gradually improve.

I've been building my own versions of the sample projects there, in effect steps 3 and 4, trying to increasingly step away from the examples and either build from what I remember or searching documentation or forums as appropriate. I intend to publish about those results here as they become available.

## Concluding remarks

The rest of lesson 0 is mostly about how to run notebooks. Jeremy focuses on AWS and Google Colab as two easy ways to run fastbook's notebooks. This is useful how-to that allows you to get set up and running code, but I won't be covering it in this post as I wanted to focus here on the advice he was giving about how to learn fastai.

I'm really excited about this course and about the reading group set up by Weights and Biases, and not only because of the topics we're covering but also to see an example to this top-down learning approach in action.
