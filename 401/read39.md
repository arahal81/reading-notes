# Reading 39

## Create a Next.js App

- To build a complete web application with React from scratch, there are many important details you need to consider:

Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
You need to do production optimizations such as code splitting.
You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.
You might have to write some server-side code to connect your React app to your data store. A framework can solve these problems. But such a framework must have the right level of abstraction — otherwise it won’t be very useful. It also needs to have great "Developer Experience", ensuring you and your team have an amazing experience while writing code.

## Next.js: The React Framework

Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.

## Setup

If you don’t have Node.js installed, install it from here. You’ll need Node.js version 10.13 or later.

### Create a Next.js app

To create a Next.js app, open your terminal, cd into the directory you’d like to create the app in, and run the following command:

    - cd nextjs-blog

    - yarn create next-app --example with-tailwindcss Name-of-your-app

    - npx create-next-app name-of-your-app --use-npm --example

### Run the development server

cd nextjs-blog npm run dev

#### Editing the starter Page

##### Download Starter Code (Optional)

`npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/navigate-between-pages-starter"`

### Image Component

import Image from 'next/image'

`const YourComponent = () => ( <Image src="/images/profile.jpg" // Route of the image file height={144} // Desired size with correct aspect ratio width={144} // Desired size with correct aspect ratio alt="Your Name" /> )`

#### Writing and Importing CSS

    - CSS and Sass (import .css and .scss files)
    - Tailwind CSS

#### Restart the Development Server

`npm run dev`
