---
title: Home
layout: home
---

# San Juan Islands Orca Sightings Service

This cloud-based service tracks the movements of orca pods around the San Juan Islands in the Salish Sea. Orcas are also known as killer whales.

Using this service, orca enthusiasts can report the location and time of their sightings off the coast of any of the San Juan Islands, making it easy for others to sight these whales from land so they don't have to charter a boat. You (the developer) can include this service in your app.

![ Photo of Orca whales](https://images.unsplash.com/photo-1602264836619-094873fa05fc?w=900&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nnx8b3JjYSUyMHdoYWxlfGVufDB8fDB8fHww)

## User community

The orca whale watching community is niche, but very active. It includes a variety of enthusiasts from around the world, and many seek the orca that frequent the San Juan Islands.

*Jeff: Is there a user community I can link to here?*

## Features of the Orca Sighting service

This is a RESTful API service with `/users` and `/sightings` resources. Each resource allows the typical GET, POST, PUT, and DELETE actions, allowing you to implement the following actions in your app:

* Create new users and sightings
* Find all or some of the users and sightings
* Update existing users and sightings
* Remove users and sightings

## Next steps

**Download the API** and **get started**! 

Also see:

* How Tos
* Tutorials
* API Reference

---
*Leaving the Just the Docs info here for reference. I'll delete this later.*

This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
