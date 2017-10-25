---
title: "Rails Tutorial SampleApp"
short_title: "SampleApp"
content_meta: "This is a code-along through the Rails Tutorial by Michael Hartl"
image_url: "images/sampleapp.png"
page_url: "/projects/sampleapp"
description: "This is a code-along through the Rails Tutorial by Michael Hartl" 
tags: ["Ruby on Rails"]
layout: project
featured: true
date: 29 Sept 2017
index_order: 2
---

First large tutorial in my quest to learn web development.

Micro Blogging site, with the following features:

- User Accounts
    - Signup & Login
    - Account Activation Email
    - Password Reset
    - Profile Page
    - Update Name, email, password
    - Validations
        - Password Length >= 6 characters
        - Email is valid format
- Micro Posts
    - Submit new Posts
    - Text <= 140 characters
    - Attach Image
        - Size < 5MB
        - Extensions: jpg, jpeg, gif, png
        - Resize on Upload
        - Production Storage on AWS S3 Bucket
- User *Feed*
    - Follow other Users
    - Followed by other Users
    - Homepage shows *Feed* of posts by Users being followed
- Hosting
    - App running on Heroku
    - DNS through AWS Route 53
    - Cloud Storage through AWS S3 Bucket using `fog`

## Links

- [Live App](http://sampleapp.hoover.ml)
- [Repo](https://github.com/machuu/railstutorial-sample_app)
- [Tutorial](https://www.railstutorial.org/book)
