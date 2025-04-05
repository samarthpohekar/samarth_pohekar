## Introduction

Hi there! 👋

I am Samarth Pohekar, and today I’ll be discussing Jekyll—what it is, why you should use it, and how to generate your own website using it.

## What is Jekyll?

Jekyll is a static site generator written in Ruby. It takes Markdown, HTML, and Liquid templates to generate a static website that can be hosted anywhere, including GitHub Pages.

It is commonly used for blogs, portfolios, documentation, and personal websites because it eliminates the need for databases or backend programming.

## Why Use Jekyll?

 **Fast & Secure** – Generates static HTML files (no database needed)
 **Easy to Use** – Write content in Markdown (.md files)
 **Built-in Blogging Support** – No extra setup required
 **Works with GitHub Pages** – Free hosting for personal sites
 **Customizable** – Use themes, plugins, and Liquid templates

## Steps to Generate Your Own Website

### 1. Install Required Dependencies

Before you start, make sure your system has the necessary dependencies:

 **Ruby** (Jekyll is built with Ruby)
 **RubyGems** (Manages Ruby packages)
 **Bundler** (Manages Jekyll dependencies)
 [**Jekyll**](https://jekyllrb.com/docs) (The static site generator itself)
 [**Git**](https://git-scm.com/downloads) (Version control for deployment)

> For Windows users: Download Ruby and it’s packages from [RubyInstaller](https://rubyinstaller.org/) and install it.
> 

### 2. Install Jekyll and Bundler

Once Ruby is installed, install Jekyll and Bundler globally by running:

```
gem install jekyll bundler

```

### 3. Verify the Installation

Check if Jekyll is installed successfully by running:

```
jekyll -v

```

### 4. Create a New Jekyll Site

Generate a new Jekyll site using:

```
jekyll new website-name

```

Then, navigate to your project folder:

```
cd website-name

```

### 5. Install Required Dependencies

Inside the `website-name` folder, install dependencies using:

```
bundle install

```

### 6. Serve Your Website Locally

To preview your website before deploying, run:

```
bundle exec jekyll serve

```

Visit http://127.0.0.1:4000/ in your browser to see your website.

## Deploying the Website on GitHub Pages

### 1. Create a GitHub Repository

Go to [GitHub](https://github.com/) and create a new repository.

### 2. Initialize Git and Push Your Site

Run the following commands inside your Jekyll project folder:

```
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <https://github.com/YOUR_USERNAME/my-website.git>
git push -u origin main

```

### 3. Enable GitHub Pages

 Go to your GitHub repository.
 Navigate to **Settings → Pages**.
 Under **Source**, select the `main` branch.
 Click **Save**.

### 4. Update `_config.yml`

In your repository, edit the `_config.yml` file and update the `url` and `baseurl` values:

```yaml
url: "<https://your-username.github.io>"
baseurl: "/website-name"

```

### 5. Access Your Live Website

Your website will now be live at:

```
<https://your-username.github.io/website-name/>

```

![jekyll](/assets/images/jekyll.png)




## Conclusion

Thank you for reading! 🎉 Every small step you take in learning something new matters. Your support keeps me motivated to share more. Keep learning, keep growing, and see you in the next post! 🚀
