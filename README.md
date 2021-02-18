This is the repository for my personal site [**Riegler.fr**](https://riegler.fr)


## Technology used

* It uses the Static Site Generator (SSG) [Next.js](https://nextjs.org/)
* It uses the [TailWindCSS](https://tailwindcss.com/) framework, [PostCSS](https://postcss.org/) and CSS Modules
* Blog articles are written in `Markdown` and converted to HTML using [remark](https://github.com/remarkjs/react-markdown). Metadata are extracted with [gray-matter](https://github.com/jonschlinkert/gray-matter)
* Blog content is optimized using [next-optimized-images](https://github.com/cyrilwanner/next-optimized-images) & [responsive-loader](https://github.com/dazuaz/responsive-loader).


## Dev, build & deploy

* ```npm run dev``` to run as Server Side rendering
* ```npm run build```to build the app as a static site (SSG) and export to ```/out````
* ```npm run serve-build``` to start http-server to serve the built site at ```127.0.0.1:8080```
