# 401 class 41 notes

**Why this matters**: This information matters because 

------------------------------------

**1. Explain the concept of dynamic routes in Next.js and how they differ from static routes.**

Dynamic routes allow the user to create dynamic content using the values of URL parameters. User can create flexible, data-driven pages by using values in square brackets in the page filename as placeholders for values that get passed as URL parameters.

They differ from static routes because static routes use fixed URLs and the content rarely changes. Content is pre-generated when built and is served as an HTML file. Pages using dynamic routes have segments that change with content that changes.

[Source](https://nextjs.org/learn/basics/dynamic-routes)

**2. Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?**

Steps include starting with the `npm run build` command, choosing a deployment platform, configuring settings (build command, ENV, domains, SSL certificates, etc), then deploy the app.

Deployment platforms include: Vercel, Netlify, Heroku, DigitalOcean, and AWS Amplify.

[Source](https://nextjs.org/learn/basics/deploying-nextjs-app0)
And a Google search of deployment platforms.

**3. How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.**

There's built-in support for static files like stylesheets and images, and by default these files are stored in the "public" directory, which are then accessible from the app's root URL. You can reference them with HTML elements or React components that load assets from the "public directory."


[Source](https://nextjs.org/docs/pages/building-your-application/optimizing/static-assets)

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!