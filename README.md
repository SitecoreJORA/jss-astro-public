# Sitecore JavaScript Software Development Kit for Astro

![Library](https://github.com/exdst/jss-astro-public/actions/workflows/publish-astro-sitecore-jss.yml/badge.svg)
![Astro projct initializer](https://github.com/exdst/jss-astro-public/actions/workflows/publish-astro-sitecore-jss.yml/badge.svg)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

This project is an implementation of Sitecore JavaScript Services Software Development Kit(SDK) for Astro. It contains Astro components and integration for JSS.
It is fully featured SDK. You can use it to build your website with Astro and Sitecore.

## Project structure

* [Astro JSS SDK](./astro-sitecore-jss/packages/astro-sitecore-jss/)
* [Astro sample project](./astro-sitecore-jss/packages/astro-sitecore-jss-sample/)
* [Astro project initializer](./astro-sitecore-jss/packages/create-astro-sitecore-jss/)
* [Sitecore](./sitecore/)

## Development usage

1. Initialize and start Sitecore instance. Please, follow instruction under [Sitecore](./sitecore/README.md) folder to setup Sitecore instance.
2. Open Sitecore Content Editor and check that there is a new SXA managed headless website under path `/sitecore/content/Headless/Astro`
3. Check your Node version using command `node -v`. If version is lower than 18, please, update it to LTS version 18+.
4. Change directory to the [Astro SDK project](./astro-sitecore-jss/packages/astro-sitecore-jss/) `cd ./astro-sitecore-jss/packages/astro-sitecore-jss/`
5. Install npm packages with `npm install`
6. Change directory to the [Astro sample project](./astro-sitecore-jss/packages/astro-sitecore-jss-sample/) `cd ./astro-sitecore-jss/packages/astro-sitecore-jss-sample/`
7. Install npm packages with `npm install`
8. Start the project with `npm run dev` command
9. Open [http://localhost:4321](http://localhost:4321) in your browser (If port 4321 is busy, different port will be used)
10. Open Sitecore Experience Editor for item `/sitecore/content/Headless/Astro/home/styleguide`

## Production usage

### Installation for production usage

1. Create Sitecore Headless website. You can use any approach:
   * [SXA managed approach](https://doc.sitecore.com/xp/en/developers/sxa/102/sitecore-experience-accelerator/create-a-headless-tenant-and-site.html)
   * Config manages site
1. Open command line
1. Run `npx @astro-sitecore-jss/create-astro-sitecore-jss@latest`
1. Follow instructions
1. Change directory to the created project
1. Start website with `npm run dev`

### Production build

1. Run `npm run build` command to build the project
1. Copy `./dist` folder to your web server

Astro support deployment to many platforms. Please, follow [Astro documentation](https://docs.astro.build/en/guides/deploy/) to deploy your website.
Some examples:

1. [Netlify](https://docs.astro.build/en/guides/deploy/netlify)
1. [Vercel](https://docs.astro.build/en/guides/deploy/vercel)
1. [AWS](https://docs.astro.build/en/guides/deploy/aws/)
1. [Azure](https://docs.astro.build/en/guides/deploy/microsoft-azure/)

## Installation for development and contribution

### Sitecore

Currently, the project supports only the Sitecore first approach. You are not able to push items to Sitecore from code.
Please follow the instructions in the [Sitecore](./sitecore/README.md) folder to set up the Sitecore instance.
It is Docker based, so you can easily run it locally with a few commands.

## NPM packages

* [Sitecore JSS Astro SDK](https://www.npmjs.com/package/@astro-sitecore-jss/astro-sitecore-jss)
* [Astro project initializer](https://www.npmjs.com/package/@astro-sitecore-jss/create-astro-sitecore-jss)

## Contacts

If you would like to see the demo, please contact  

* [Email](mailto:at@exdst.com)
* [LindedIn](https://www.linkedin.com/in/anton-tishchenko-b45b2923/)

## Articles

* Sitecore JavaScript Software Development Kit for Astro, [EXDST blog](https://exdst.com/posts/20231002-sitecore-astro)
* Interactive React Islands with Sitecore and Astro, [EXDST blog](https://exdst.com/posts/20231122-sitecore-astro-react)
* Interactive Vue Islands with Sitecore and Astro, [EXDST blog](https://exdst.com/posts/20231123-sitecore-astro-vue)
* Interactive Angular Islands with Sitecore and Astro, [EXDST blog](https://exdst.com/posts/20231123-sitecore-astro-angular)
* Sitecore XM Cloud and Astro Web Framework, [EXDST blog](https://exdst.com/posts/20231206-sitecore-xm-cloud-astro)
* Starting Your First Sitecore Astro Project, [EXDST blog](https://exdst.com/posts/20240103-first-sitecore-astro-project)
* Creating Your First Sitecore Astro Rendering, [EXDST blog](https://exdst.com/posts/20240104-sitecore-astro-rendering)
* Migration of Sitecore Vue Website to Astro, [EXDST blog](https://exdst.com/posts/20240202-sitecore-jss-vue-astro-migration)
* Migration of Sitecore React Website to Astro, [EXDST blog](https://exdst.com/posts/20240403-sitecore-react-astro)
* Astro + React + Angular together, [EXDST blog](https://exdst.com/posts/20240829-astro-react-angular-together)
* Deploy Astro to XM Cloud, [EXDST blog](https://exdst.com/posts/20250127-sitecore-xm-cloud-astro)
* Sitecore + Astro, [Youtube, SUG Latam](https://www.youtube.com/watch?v=pP6pcaO_FhY)
* Sitecore Headless Software Development Kit for Astro, [Youtube, SUGCON](https://www.youtube.com/watch?v=PzOSONAdxe8)
* Astro Verticals Demo Case Study, [EXDST site](https://exdst.com/astro-demo)
* Release 1.0.1, [EXDST blog](https://exdst.com/posts/20250303-sitecore-astro-jss-1-0-1-release)
* Sitecore Astro Verticals Demo Website: Feature Comparison with Next.js, [EXDST blog](https://exdst.com/posts/20250223-sitecore-astro-verticals-features-list)
* Sitecore Astro Verticals Demo Website: Next.js vs Astro Components Comparison, [EXDST blog](https://exdst.com/posts/20250221-sitecore-astro-verticals-components)
* Sitecore Astro Verticals Demo Website: Performance, [EXDST blog](https://exdst.com/posts/20250225-sitecore-astro-verticals-performance)
* Sitecore Astro Verticals Demo Website: Running Locally, [EXDST blog](https://exdst.com/posts/20250217-sitecore-astro-verticals-local)
* Sitecore Astro Verticals Demo Website: Running on Sitecore Demo Portal, [EXDST blog](https://exdst.com/posts/20250214-sitecore-astro-verticals-demo-portal)
* Sitecore Astro Verticals Demo Website: The Process, [EXDST blog](https://exdst.com/posts/20250213-sitecore-astro-verticals-demo-process)
* Sitecore Astro Verticals Demo Website, [EXDST blog](https://exdst.com/posts/20250226-sitecore-astro-verticals-announcement)

## Demo Website
You can see Astro together with Sitecore in action in [this repository](https://github.com/exdst/Sitecore.Demo.XMCloud.Verticals). It is a fork of the Sitecore Next.js Demo website, reimplemented on Astro, which proves Astro capabilities and better Astro performance compared to Next.js.

## Contributors

* Anton Tishchenko, [GitHub](https://github.com/antonytm), [LinkedIn](https://www.linkedin.com/in/anton-tishchenko-b45b2923/)
* Bogdan Druziuk, [GitHub](https://github.com/bdruziuk), [LinkedIn](https://www.linkedin.com/in/bogdan-druziuk-50069763/)
* Oleksandr Melnyk, [GitHub](https://github.com/OlekMel)
* Stanislav Chernetsky, [GitHub](https://github.com/stanislavSV)
* Vasyl Gavrylyuk, [GitHub](https://github.com/vsegrad)
* Vadym Shcherban, [GitHub](https://github.com/Lawliet1701) 

Sponsored by [EXDST](https://exdst.com/)
