# Polaris Documentation

 This **Polaris proposal tool documenation** uses the Docsy
theme component as a hugo module, together with other module dependencies:

```console
$ hugo mod graph
hugo: collected modules in 566 ms
hugo: collected modules in 578 ms
github.com/google/docsy-example github.com/google/docsy@v0.7.1
github.com/google/docsy-example github.com/google/docsy/dependencies@v0.7.1
github.com/google/docsy/dependencies@v0.7.1 github.com/twbs/bootstrap@v5.2.3+incompatible
github.com/google/docsy/dependencies@v0.7.1 github.com/FortAwesome/Font-Awesome@v0.0.0-20230327165841-0698449d50f2
```

You can find detailed theme instructions in the [Docsy user guide][].



## Running the website locally

Building and running the site locally requires a recent `extended` version of [Hugo](https://gohugo.io).
You can find out more about how to install Hugo for your environment in our
[Getting started](https://www.docsy.dev/docs/getting-started/#prerequisites-and-installation) guide.

Once you've made your working copy of the site repo, from the repo root folder, run:

```bash
hugo server
```

## Running a container locally

You can run the guide site inside a [Docker](https://docs.docker.com/)
container, the container runs with a volume bound to the `docsy-example`
folder. This approach doesn't require you to install any dependencies other
than [Docker Desktop](https://www.docker.com/products/docker-desktop) on
Windows and Mac, and [Docker Compose](https://docs.docker.com/compose/install/)
on Linux.

1. Run the built image

   ```bash
   docker compose up
   ```


1. Verify that the service is working.

   Open your web browser and type [http://localhost:1313](http://localhost:1313) in your navigation bar,
   This opens a local instance of the guide homepage. You can now make
   changes to the guide and those changes will immediately show up in your
   browser after you save.

### Cleanup

To stop Docker Compose, on your terminal window, press **Ctrl + C**.

To remove the produced images run:

```bash
docker compose rm
```
For more information see the [Docker Compose documentation][].



[alternate dashboard]: https://app.netlify.com/sites/goldydocs/deploys
[deploys]: https://app.netlify.com/sites/docsy-example/deploys
[Docsy user guide]: https://docsy.dev/docs
[Docsy]: https://github.com/google/docsy
[example.docsy.dev]: https://example.docsy.dev
[Hugo theme module]: https://gohugo.io/hugo-modules/use-modules/#use-a-module-for-a-theme
[Netlify]: https://netlify.com
[Docker Compose documentation]: https://docs.docker.com/compose/gettingstarted/
