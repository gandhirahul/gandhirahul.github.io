This repository is forked from: https://github.com/sproogen/modern-resume-theme

*A modern simple static resume template and theme. Powered by Jekyll and GitHub pages.*  
*Host your own resume on GitHub for **free!***

# My Portfolio

Welcome to my portfolio repository! This repository hosts the source code for my personal website, where I showcase my professional experience, projects, and interests.

## About Me

👋 Hi there! I'm Rahul Gandhi, a passionate frontend engineer with over 10 years of experience in building innovative and user-centric web applications. I specialize in JavaScript, particularly ReactJS, and have a keen eye for creating engaging user interfaces.

💼 In my professional journey, I've had the privilege of working with leading companies like Bumble and Roposo, where I led diverse projects and teams, optimizing performance and user experiences. I'm committed to delivering high-quality code and fostering collaboration within cross-functional teams.

🛠️ This portfolio is built using Jekyll, a static site generator that allows for efficient development and easy maintenance. Leveraging Jekyll's simplicity and flexibility, I've created a fast, responsive, and easily customizable website to showcase my skills and achievements.

## Features

- Responsive design to ensure optimal viewing across various devices.
- Markdown-based content management for easy updating and maintenance.
- Optimized performance for fast loading times and smooth user experience.
- Clean and intuitive navigation to guide visitors through my portfolio.

----

## Installation & setup guide
This template is designed to be hosted using GitHub pages and so that's what these instructions will cover. If you plan on hosting it seperately then there might be some extra steps that we wont cover.

Before starting it might be useful to familiarise yourself with [Jekyll](https://jekyllrb.com/docs/home/), [Markdown](https://www.markdownguide.org/getting-started) and [GitHub pages](https://pages.github.com/).

### Step 1 - GitHub
Start by creating an account on [GitHub](https://github.com/join)

### Step 2 - Create Repository
Create a repository on GitHub to hold your files and host your resume. You can find out how to do that [here](https://pages.github.com/)

### Step 3 - Download Resume Template
Download and extract the following zip into the git repository you have just created. [resume-template.zip](https://github.com/sproogen/modern-resume-theme/archive/gh-pages.zip)

### Step 4 - Push it
Commit and push the resume template to github
```
$ git add --all
$ git commit -m "Initial resume setup"
$ git push -u origin master
```
### Step 5 - See it
You should now be able to see the demo resume template using this theme at `[your-username].github.io`

----

## Running locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

1. Clone your resume repository locally *(if you haven't already)*
2. `cd [your-repository-name]`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser.

*Note: You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

----
## Development

### Locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

*Note: You will need version `1.15.2` of bundler, as this is the only version that Heroku supports.*

1. Fork and or clone this repository locally
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

***Note:** You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

### Docker

If you have docker installed you can simply run `docker-compose up` to launch the site in a container, it will then be hosted at `http://localhost:4000`

----

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
