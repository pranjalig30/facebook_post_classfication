# Assignment 1: Facebook Post Classification

## Background

As one of the largest social media platforms, Facebook offers a valuable opportunity for businesses to connect with their customers. Users generate numerous posts on business pages, which may include complaints, questions, or appreciation. Understanding these posts can help businesses gain insights into customer needs and preferences.

## Dataset and Task

For this assignment, we use a labeled dataset named `FB_posts_labeled.txt`, a tab-delimited file with the following fields:
- `postId`: Unique identifier for each user post (7961 posts in total).
- `message`: Text content of the post.
- `Appreciation`: Binary indicator (0/1) for appreciation posts.
- `Complaint`: Binary indicator (0/1) for complaint posts.
- `Feedback`: Binary indicator (0/1) for feedback posts (questions and suggestions).

The content categories (Appreciation, Complaint, Feedback) are mutually exclusive and were labeled by humans. Your task is to build a text classifier to predict the content category of a post based on its textual content.

## Notebook Summary

### Text Cells

#### Background
- Facebook is a significant platform for businesses to engage with customers.
- User posts on business pages provide valuable insights into customer preferences.

#### Dataset and Task
- Use the `FB_posts_labeled.txt` dataset.
- The dataset is tab-delimited with fields: `postId`, `message`, `Appreciation`, `Complaint`, `Feedback`.
- Task: Build a classifier to predict the content category of a post.
