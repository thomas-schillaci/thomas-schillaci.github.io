---
title: Machine Learning internship - Hardis group
categories:
  - Machine Learning
  - Internships
tags:
  - Unsupervised Learning
  - Supervised Learning
  - Reinforcement Learning
  - Keras
  - Learning platform
  - Full stack
excerpt: In this post, I talk about a three-month internship I took in summer 2019 as an engineering student, where my mission was to help in the development of a learning platform and create Machine Learning courses for it.
gallery:
  - image_path: /assets/images/unsupervised_charts.jpg
    alt: "Unsupervised learning algorithms chart"
    title: "Unsupervised learning algorithms chart"
  - image_path: /assets/images/unsupervised_denoising.jpg
    alt: "Denoising images with unsupervised learning"
    title: "Denoising images with unsupervised learning"
  - image_path: /assets/images/vae_3D_space.jpg
    alt: "VAE 3D latent space visualization"
    title: "VAE 3D latent space visualization"
gallery2:
  - image_path: /assets/images/mnist.jpg
    alt: "Samples from the MNIST dataset"
    title: "Samples from the MNIST dataset"
  - image_path: /assets/images/mnist2.jpg
    alt: "Samples from the MNIST dataset"
    title: "Samples from the MNIST dataset"
  - image_path: /assets/images/neural_network.jpg
    alt: "A simple neural network"
    title: "Can a neural net find which animals are present in the previous pictures?"
gallery3:
  - image_path: /assets/images/cat.jpg
    alt: "A cat"
    title: "A cat - Photo by <a target=_blank href=https://unsplash.com/@michaelsum1228?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>Michael Sum</a> on <a target=_blank href=https://unsplash.com>Unsplash</a>"
  - image_path: /assets/images/sobel_cat.jpg
    alt: "A cat passed through a sobel filter"
    title: "A cat passed through a sobel filter"
  - image_path: /assets/images/gaussian_cat.jpg
    alt: "A cat passed through a gaussian filter"
    title: "A cat passed through a gaussian filter"
gallery4:
  - image_path: /assets/images/snake.jpg
    alt: "Snake - the game"
    title: "<a target=_blank href=https://commons.wikimedia.org/wiki/File:Cgasnake.png title=via_Wikimedia_Commons>Thomas Jensen</a> / <a target=_blank href=http://creativecommons.org/licenses/by-sa/3.0>CC BY-SA</a>"
  - image_path: /assets/images/tic-tac-toe.jpg
    alt: "A board of tic-tac-toe"
    title: "A board of tic-tac-toe"
  - image_path: /assets/images/poker.jpg
    alt: "A game of poker"
    title: "Photo by <a target=_blank href=https://unsplash.com/@mparzuchowski?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText >Michał Parzuchowski</a> on <a target=_blank href=https://unsplash.com>Unsplash</a>"
---

In this post, I talk about a three-month internship I took in summer 2019 as an engineering student, where my mission was to help in the development of a learning platform and create Machine Learning courses for it.

{% capture fig_img %}
![Foo]({{ '/assets/images/christopher-burns-Kj2SaNHG-hg-unsplash.jpg' | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption style="margin: auto;">Photo by <a href="https://unsplash.com/@christopher__burns?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Christopher Burns</a>
  on <a href="https://unsplash.com/s/photos/machine-learning?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a></figcaption>
</figure>

When I was in high school, Richard Feynman was only a famous scientist whose work was too complicated for me to grasp.
This was the case until I discovered [his physics lectures](https://www.feynmanlectures.caltech.edu/) and soon after a few books about his life.

Today, Richard Feynman is one of the people who has had a lot of influence on my educational background.
He has a way to create representations of concepts to structure his reasoning that makes his explanations so clear, that I hope one day I will be able to create content with this level of quality.

With that in mind, I think you can imagine how I felt when a company offered me an intership where I would have had to create courses on a topic I loved.

## My internship at Hardis Group

Hardis Group is a french software firm that employs 1'000+ people for a turnover of €115M+ in 2018.

My internship topic had two perspectives: full stack development and Machine Learning courses creation, I talk briefly about the first one before reflecting about the second--and big--one.

### Full stack development

On my first day at Hardis Group, I joined the team in charge of creating their online learning platform. My mission was to help in the development process and make it evolve so that it could support my Machine Learning courses.

The stack's components I worked on are:
- **Vue.js** for the front-end
- **Python** + **Flask** for the back-end
- **Kubernetes** to run the user's code (as part of the platform's exercices)
- **AWS** cloud solutions

At the end of my internship, my contribution accounted for 25% of the repository's source code. For example, I've implemented an editor supporting Markdown and LaTeX
with real-time rendering of what the course would look like if posted (I will upload an open-source version of the markdown + LaTeX real-time rendering on my github sometime).

### Machine Learning courses

The main mission I was assigned at Hardis Group was the creation of introduction courses to Machine Learning ; I created four of those:

#### 1. Unsupervised I - autoencoders and Fashion MNIST
    
{% include gallery caption="A few use cases of unsupervised learning" %}

This course covered the following topics:
- What is unsupervised learning?
- Data clustering
- Auto-encoders
- Exercice: creating an unsupervised image classifier (images from Fashion MNIST)

#### 2. Supervised I - Keras and MNIST

{% include gallery id="gallery2" caption="Can a neural network find which digits are present in these pictures?" %}

This course covered the following topics:
- What is supervised learning?
- Neural networks basics
- Creating a MNIST image classifier using Keras
- Exercice: create a neural network exceeding 90% of categorical accuracy on MNIST (we are limited by the platform's ressources)

#### 3. Supervised II - Keras and CNNs

{% include gallery id="gallery3" caption="Convolutional neural nets perform very well to identify cute animals in pictures" %}

This course covered the following topics:
- What is a convolutional neural network?
- Convolutional layers
- Pooling layers
- Keras implementation
- Convolutional network architectures
- Exercice: create a neural network exceeding 75% of categorical accuracy on Fashion MNIST

#### 4. Q-learning and Snake

{% include gallery id="gallery4" caption="Games that can be played by reinforcement learning algorithms" %}

This course covered the following topics:
- What is reinforcement learning?
- Q-learning
- Exercice: implement a Q-learning algorithm that can win a 3x3 game of Snake 60% of the time after 30s of training (I implemented a browser interface so that the user could visualize their AI winning a game of Snake)

## My internship: one year later

As I am writing this post, my portfolio is very recent and I am currently writing content for it.
My internship at Hardis Group took place a year ago, this gave me plenty of time to think about it.

Here are a few things I learned:
- Explaining a topic helps you mastering it. Writing introduction courses about Machine Learning topics helped me realize there were a few things I had not fully understood
- I really enjoy creating teaching content. I enjoy it so much that I have enrolled in the Educational Technology class at Georgia Tech for Fall 2020
- Full stack development and modern stacks are fascinating, I really had a lot of chance working on this topic I had never approached before
- Cloud technologies and Docker/Kubernetes are also very impressive


Working in a software development firm is cool. Honestly, I woke up every day eager to go to work.

However, I will try to aim at a position more involved in managment after obtaining my PhD ; I want to be able to work on projects while leading the team developing it.
