---
title: My Gatsby Blog Site
date: "2022-06-22T10:00:00.169Z"
description: This blog is about how I created my blog site using Gatsby.
---


I knew after the first two cloud projects I completed, I needed a blog to write about my experience. I didn’t want to design a whole new website, but I knew I wanted to use [Azure Static Web Apps]( https://docs.microsoft.com/en-us/azure/static-web-apps/overview). Azure Static Web Apps is “a service that automatically builds and deploys full stack web apps to Azure from a code repository.” I wanted to use that because I wanted to see how it would work because with the Cloud Resume, I could have used it but then I would not have learned all the detailed steps which I undertook to learn the different aspects of Azure.

I wanted to find something simple where a template already existed for the blog site, and all I had to do was configure it, modify the content, and deploy it using Azure Static Web Apps. I found my solution on the [Microsoft Developers Youtube page](https://www.youtube.com/watch?v=IZbcpUIke8s), which had an explanation to complete what I wanted to accomplish.

As a result, I undertook my 3rd cloud project of creating a Gatsby blog site. [Gatsby]( https://www.gatsbyjs.com/) is an open-source static website generator (SSG) that is based on the frontend development framework React and makes use of Webpack and GraphQL technology. It can be used to build static sites that are web apps, following the latest web standards, and optimized for speed and security.

###### 1) Get the template and set up GitHub repository

I first downloaded the template and then set up my GitHub repository. I cloned the repository to my desktop.
Here is my [repository](https://github.com/AnupK-GH/gatsby-blog-site).



###### 2) Next I installed Gatsby and ran a local build

To install Gatsby I ran the command:  ```npm install Gatsby-cli -g```

Next after added all the files from the template I ran another command: 

```npm install ```

That installed any of the required node modules that will power my Gatsby website. 

Finally I typed  ```gatsby develop``` , and then I was able to see my local build here: http://localhost:8000.
