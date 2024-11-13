# Ozmovies

This is a web application that covers only the early years of Australian talkies in the movie industry. It is intended as a general guide to the era of VHS and DVD-published Australian films, now drawing to a close. It has been developed for the purposes of study, review, and information. More movies will be added as we get around to it.

Ozmovies only claims copyright to its original content and site format. All other material is copyrighted by the original holders of copyright. 

## Technology Stack

This is a [Next.js](https://nextjs.org/) application with [MongoDB](https://www.mongodb.com/)

- Next.js v14.2.14
- MongoDB v7.0

## Requirements

For development, you will need to install `Node.js v20.x (recommended) or greater`, a node global package, `NPM`, and `MongoDB v7.0 (recommended)` in your environment.

### Prerequisites

Node.js (lts)
MongoDB

## App Setup

You can configure this app by following the instructions mentioned below:

### Clone Repository

Run the command `git clone https://github.com/UmerSurhkel-Projects/oz-movies-front` to clone this public repository.

### Install Packages

At the root directory of the application, run the following command to install packages:

```bash
npm i
```

If the installation fails due to conflicts with peer dependencies, try running the command with the `--legacy-peer-deps` flag:

```bash
npm i --legacy-peer-deps
```
Please note that, if you see conflicts/warnings while installing, this is because an outdated version of `eslint` is used in the application. We'll stick with `eslint@8.x` temporarily since `eslint-config-next` and other related plugins are only compatible with `eslint@8.x`, until these plugins release updates for `eslint@latest`.

### Configure App

Add a `.env` file at the root of the project. Sample values are available in the `.env.example` file.

### Run Project Locally

Start running a project with the following command:

```bash
npm run dev
```

### Build Project Locally

To build a project locally run the following command:

```bash
npm run build
```

### Port

It would run on port `3000` if you provide PORT `3000` in the `.env` file.

The required PORT can be added in the `.env` file.

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Error Handling

- The error messages returned by the API are informative. 
- Handled unexpected errors using try-catch statements where needed.
- Returned the error messages where required.
- Tested error scenarios and unexpected errors.

## Additional Information

- All the SEO best practices and standard coding guidelines have been followed in the app.
- Only the required dependencies and devDependencies are installed in the app.
- All the required linting tools are configured in the app.
- This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.
- This project uses [`Redis`](https://redis.io/) to cache the results on the server.
- This project uses the rich text editor [`CKEditor`](https://ckeditor.com/) to create any type of content in the app.
- This project also uses the [`Amazon S3`](https://aws.amazon.com/s3/) to upload files to Amazon S3.

## Deploy on Vercel

[Site URL](https://www.ozmovies.com.au/)

[Admin Console URL](https://www.ozmovies.com.au/admin/login)

## Documentation

[API Documentation](https://documenter.getpostman.com/view/7228218/2s9YJaZ4s4)