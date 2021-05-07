# Finding trends in Hacker News Posts

## Introduction

In this project, we work with the data of the technology site [Hacker News](https://news.ycombinator.com/).

Hacker News is a site started by the startup incubator [Y Combinator](https://www.ycombinator.com/), where user-submitted posts are voted and commented upon, similar to reddit.

We use Python run on a Jupyter Notebook to analyze the data.

- Data: [hackers_new.csv](https://github.com/bertacv/hacker-news-posts/blob/main/data/hacker_news.csv)  or [original dataset](https://www.kaggle.com/hacker-news/hacker-news-posts)
- Notebook: [Exploring Hacker New Posts.ipynb](https://github.com/bertacv/hacker-news-posts/blob/main/notebooks/Exploring%20Hacker%20New%20Posts.ipynb)

The data set was reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions.

This is a project of the Dataquest learning program.

## Objective

We analyse two types of posts - those whose title begin with either `Ask HN` or `Show HN`.

- `Ask HN` posts are used to ask the Hacker News community a specific question.
- `Show HN` posts are used to show the Hacker News community a project or product.

The goal of this project is to compare these two types of posts to determine:

- Do `Ask HN` or `Show HN` receive more comments on average?
- When is the best time to create a post in order to receive more comments?
