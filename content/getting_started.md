+++
title = "Getting Started"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2014-04-02"
categories = [
    "Development",
    "golang",
]
menu = "main"
weight = 20
toc = true
draft = false
+++

## Step 1. Clone repository

Go to [Hugo Landing Page repository](https://github.com/spf13/hugo/releases) and clone it into your computer.

```bash
git clone https://xxx.com/xxx/xxx
```

## Step 2. Build the web pages

Run ``hugo`` command  from the new directory to build all of the web content with compiling their assets Javascript and Scss.

```bash
cd Hugo-Landing-Page
hugo
```

After runninng commands, directory named ``public`` will  be created.
Files in it are all you needed when you deploy the landing page.

## Step 3. Start server

Start server as follow:

### Hugo server

```bash
hugo server
```

Now, access ``http://localhost:1313`` from your web browser.

### Docker container

You can also start server by the Docker container (contains Nginx).

```bash
docker-compose up -d
```

## Step 4. Have fun

The best way to learn something is to play with it.
