[![Contentstack](https://camo.githubusercontent.com/d24f513afa94a4a762533d54a0f590300dbd0413/68747470733a2f2f7777772e636f6e74656e74737461636b2e636f6d2f646f63732f7374617469632f696d616765732f636f6e74656e74737461636b2e706e67)](https://www.contentstack.com/)


# Create a marketing website using Gatsby

About Contentstack: Contentstack is a headless CMS with an API-first approach that puts content at the centre. It is designed to simplify the process of publication by separating code from content.

About this project: Create professional marketing-themed website using Gatsby.

<img src='https://github.com/contentstack/gatsby-starter-contentstack-internationalization/blob/master/data/readme-assets/home-page-screenshot.png?raw=true' width='650'/>
<img src='https://github.com/contentstack/gatsby-starter-contentstack-internationalization/raw/master/data/readme-assets/home-page-screenshot.png?raw=true' width='650'/>


## Live Demo

You can check the [live demo](https://gatsby-starter-topaz.vercel.app/) to get first-hand experience of the website.

## Prerequisites

- Install [nodejs](https://nodejs.org/en/) on your system.
- Install Gatsby CLI.  

`npm install -g gatsby-cli`

## Clone the repo

Clone the following repo. It contains all the required dependencies.

`git clone https://github.com/contentstack/gatsby-starter-contentstack-i18n.git`

## Install dependencies 

Go to the gatsby-starter-contentstack folder, and run the following:

- `cd gatsby-starter-contentstack`
- `npm install`

This downloads the required files and initializes the site.

## Update Contentstack secrets

Copy the `.env.sample` file to `.env.development` and `.env.production` and update with your Contentstack details, including your API key and delivery token.

It should end up looking something like:

```
CONTENTSTACK_API_KEY='Your Stack API Key'
CONTENTSTACK_DELIVERY_TOKEN='Stack delivery token'
CONTENTSTACK_ENVIRONMENT='development'
```

## Run the website

`npm run develop`

## Tutorial

We have created an in-depth tutorial on how you can create a website using Gatsby. By following the steps given in the tutorial, design a website similar to the one given in the demo.

[Create a marketing website using Gatsby](https://www.contentstack.com/docs/example-apps/getting-started-with-gatsby-and-contentstack/)

**More resources:**

- [Contentstack documentation](https://www.contentstack.com/docs/)
- [Contentstack + Gatsby app tutorial](https://www.contentstack.com/docs/developers/sample-apps/build-a-sample-website-using-gatsby-and-contentstack)