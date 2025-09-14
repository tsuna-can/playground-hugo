+++
date = '2025-09-14T18:24:01+09:00'
title = 'About Hugo'
categories = ['tech']
tags = ['hugo', 'SSG', 'Golang']
+++


# Tutorial of Hugo !

This is test article to confirm how to use Hugo.

Can I create simple blog with this framework??


## What is Hugo?

Hugo is a static site generator (SSG) written in Go (Golang).  
It is known for its speed and flexibility, making it a popular choice for building websites and blogs.
You can find more details from [official site](https://gohugo.io/).

## Getting Started

To get started with Hugo, you can follow these steps:
1. Install Hugo: You can download and install Hugo from the [official installation guide](https://gohugo.io/getting-started/installing/).
2. Create a new site: Use the command
    ```bash
    hugo new site mysite
    ```
    to create a new Hugo site. 
3. Add a theme: Choose a theme from the [Hugo themes](https://themes.gohugo.io/) and add it to your site.
4. Create content: You can create new content using the command
    ```
    hugo new article/my-first-post.md
    ```
5. Start the server: Use the command
    ```
    hugo server
    ```
    to start a local development server and view your site in the browser.
6. Build the site: When you're ready to deploy your site, use the command
    ```
    hugo
    ```
    to generate the static files in the `public` directory.
7. Deploy: You can deploy the contents of the `public` directory to your web server or hosting service.