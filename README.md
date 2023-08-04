# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

Related docs could be found [here](https://docusaurus.io/docs).

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Access

Enter `sidebar.js` to add docs to side navigation menu.
Enter `/docs` to find and add new docs to Documentation.
Enter `/blog` to find and add new blog posts to Blog.
