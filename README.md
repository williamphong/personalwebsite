## Personal Website

Hi, my name is William Phong and this is my portfolio website! This is a project done to learn Next.js, Typescript, and Tailwind. Part of the design and css come from websites that have inspired me - https://brittanychiang.com and https://carlbeaverson.com. ESLint and Prettier were also utilized to streamline my development process. New features are developed on my test branch. This readme will go through my process and thoughts as I built this site.

## Vercel Deployment

This site was published using Vercel's hobby tier and Porkbun's domain registrar system.
![porkbun](public/images/readme/domain.png)

![vercel dns](public/images/readme/dns.png)

Adding the DNS settings from Vercel to Porkbun was relatively straightforward. In Porkbun, I needed to create two A records with the host of "www" and "" with the answer provided by Vercel. Everything else was left default and after adding the records, Vercel would automatically detect and route.

After connecting a GitHub repository to Vercel, Vercel handles the branches within the repo and creates deployments for each one. The production deployment utilizes the main branch, which shows up on waphong.com The test branch creates preview deployments that are accessible through a link provided by vercel.
![deployments](public/images/readme/deployments.png)

## Plugins

Vercel web and speed analytics are available by installing the plugins and placing them in the code.
![web analytics](public/images/readme/webanalytics.png)
![speed analytics](public/images/readme/speedanalytics.png)

## packages

pqoqubbw, cursify spotlight, lucide, betterauth
![shadcn](https://ui.shadcn.com/)
![react tip tap editor](https://reactjs-tiptap-editor.vercel.app/guide/getting-started.html)

https://transfonter.org/
