# Reading 40: React 4

## Next.js - Dynamic Routes

Statically Generate Pages with Dynamic Routes

### To create dynamic routes, follow these steps

- Create a page called [id].js, pages inside square brackets are dynamic routes.
- inside this page add that code that renders any page as usual.
- Exports an async function called getStaticPaths from this page, that returns a list of possible values for id.
- Implement getStaticProps function to fetch necessary data with a given id.

### Implement getStaticPaths

- Import and add a layout function inside the [id].js page.
- Open the original page and add a getAllPostIds function that will return the list of filenames(excluding .md)
- Import getAllPostIds function to the [id].js page.

## Next.js - Deployment

#### Vercel (Recommended)

    The easiest way to deploy Next.js to production is to use the Vercel platform from the creators of Next.js. Vercel is an all-in-one platform with Global CDN supporting static & Jamstack deployment and Serverless Functions.

#### Getting started

-Sign up to Vercel.

- After signing up, you’ll arrive on the “Import Project” page. Under “From Git Repository”, choose the Git provider you use and set up an integration. (Instructions: GitHub / GitLab / BitBucket).

- After importing, it’ll deploy your Next.js app and provide you with a deployment URL. Click “Visit” to see your app in production.

#### Workflow to use. Vercel supports

    what we call the DPS workflow: Develop, Preview, and Ship.

**Develop**: Write code in Next.js. Keep the development server running and take advantage of React Fast Refresh.

**Preview**: Every time you push changes to a branch on GitHub / GitLab / BitBucket, Vercel automatically creates a new deployment with a unique URL. You can view them on GitHub when you open a pull request, or under “Preview Deployments” on your project page on Vercel.

**Ship**: When you’re ready to ship, merge the pull request to your default branch (e.g. main). Vercel will automatically create a production deployment.
