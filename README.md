<img src="https://assets.website-files.com/61a888508b7cccb7485cdac2/61b31d9009792071f950394b_logo_dscovr.svg">

# PHP Fullstack Developer Code Challenge </br> Building a YouTube 📺 "micro" 🔬 clone.

## Abstract

The code challenge is an opportunity to familiarize yourself with the technologies and domains you will be working on daily here at [DSCOVR](https://dscovr.io)

We understand that your time is valuable, so please take your time. We are also open to negotiating an extension if necessary.
It is important to complete it partially rather than not doing it at all. Try to push beyond your comfort zone 💪.

We believe that development should be an enjoyable experience, and we hope this code challenge will be stimulating and entertaining for you.

Red 🔴, Green ✅, Refactor 📝 and have fun.

## Goal

Your goal is to develop a "micro" clone of YouTube using this mandatory set of technology:

* [Vue.js]( https://vuejs.org/) for the frontend + [TypeScript](https://www.typescriptlang.org/)
* [GraphQl](https://graphql.org/) with the [Lighthouse package](https://lighthouse-php.com/) for the APIs
* [Laravel](https://laravel.com/) for the backend.
* Optionally [TailwindCSS](https://tailwindcss.com/)

The project should implement key features such as:

* Authentication (mandatory)
* Video upload (mandatory)
* Video listing and details (mandatory)
* Video Processing (optional)
* Search (optional)

If you enjoy implementing other features and at your discretion, we will evaluate it positively;
if you want to implement another feature instead of the optional one (the search), let's hear it and discuss it together.

## Features by features

### Authentication [mandatory]

* Users should be able to sign up and log in to the platform.

### Video Upload [mandatory]

* Users should be able to upload videos
* Implement a way to produce a video thumbnail
    * allow users to select either a thumbnail frame or a video frame.
    * or allow users to upload a custom thumbnail image.
* Store video details and metadata, such as:
    * video file 📺
    * title
    * description
    * uploader information (the user!)
    * other video metadata (BONUS) 🎁

### Video listing and details [mandatory]

* Implement a video feed with infinite scroll functionality.
* Create a video details page that displays:
    * Video player with the option to play the video.
    * Video title, description, and uploader information.
    * A section for user comments related to the video (BONUS)

### Video Processing [optional]

* Develop a long-running task (in your preferred language) for processing uploaded video files to apply a custom watermark:
    * Enable the addition of a custom watermark (text or image) to the video.
    * Implement asynchronous processing to handle multiple requests simultaneously.
    * Explain the challenges in ensuring compatibility with different video resolutions and aspect ratios.
    * Use the libraries of your choice

### Search [optional]

* Implement a search feature allowing users to search for videos by [title, description, uploader]
* Use the libraries of your choice

## Additional requirements

- Use GIT and preserve all commits.
- Implement proper error handling throughout the application.
- Write clean and maintainable code following best practices and design patterns (SOLID principles can be helpful).
- Implement automated testing for components/features that you think it is important to test (choose the appropriate type of test; avoid end-to-end tests for time constraints) without aiming for 100% code coverage.
- A clear and concise README.md (you can write whatever you want, but it should mainly explain architecture choices, how to build, how to run tests, etc.).
- Ensure that the project has a well-structured directory layout.

## Infra requirements

We highly value containerized applications. Therefore, we would be extremely pleased if you utilized containers for local development, test execution, and application running.

Additionally, providing documentation on expediting the build and testing process would be beneficial. Furthermore, it would be highly appreciated if you created a Makefile for automation.

## Extra for 🥷

- If observability is an indispensable development component, implement a structured log.
- A well-done deployment process is based on a CI/CD; create a CI/CD pipeline to deploy the app in your preferred IaaS/PaaS, creating the infra components with declarative tools such as Terraform.

## Submission

Please submit your project as a Git repository using `git bundle` with all commits preserved, or share it with us on GitHub or Gitlab.

## Our stack in detail

### Lang:
  - PHP
  - TS
  - Python

### API's development/presentation:
  - GraphQL
  - Rest API

### Frameworks:
  - Laravel
  - Vuejs
  - Tailwindcss
  - Livewire

### INFRA:
  - Laravel Vapor
  - AWS
  - Terraform
  - Docker

### Tooling:
  - Eslint + Prettier
  - vite (bundler)
  - test (frontend unit test) phpunit (Pest)
  - turborepo
  - Gitlab CI/CD
  - Storybook + msw
  - Phrase
  - Sentry
  - gsap

## Contacts:

For any information: [https://linktr.ee/mauro.malvestio](https://linktr.ee/mauro.malvestio)
