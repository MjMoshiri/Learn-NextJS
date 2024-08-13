# Next.js Learning Journey

A Next.js Blog project to demonstrate the concepts learned while working with Next.js. You can find the deployed project [here](https://nextjs-op.vercel.app/).

## Concepts Learned

- [Static Generation](https://nextjs.org/docs/pages/building-your-application/rendering/static-site-generation) : the page HTML is generated when you run next build. This HTML will then be reused on each request. It can be cached by a CDN.
- [Automatic Static Optimization](https://nextjs.org/docs/pages/building-your-application/rendering/automatic-static-optimization)
- [Components](https://nextjs.org/docs/app/api-reference/components)
- [Routing](https://nextjs.org/docs/pages/building-your-application/routing)
    - [Pages](https://nextjs.org/docs/basic-features/pages)
    - [API](https://nextjs.org/docs/api-routes/introduction)
    - [Dynamic Routes](https://nextjs.org/docs/routing/dynamic-routes)
        - [getStaticPaths](https://nextjs.org/docs/pages/api-reference/functions/get-static-paths) : will generate a list of paths to pre-render based on the data returned from the function
            - `fallback` : `false` will return a 404 page if the path doesn't exist, `true` will allow the page to be generated on the fly if it doesn't exist ([ISR](https://nextjs.org/docs/pages/building-your-application/data-fetching/incremental-static-regeneration))
        - [getStaticProps](https://nextjs.org/docs/pages/api-reference/functions/get-static-props) : will pre-render a page at build time using the props returned from the function
- [Deployment](https://nextjs.org/docs/deployment)


