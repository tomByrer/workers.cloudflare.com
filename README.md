# Built with Workers


## About

Built with Workers is an open-source website showcasing websites and other projects built with Cloudflare Workers.

[Visit the site →](https://workers.cloudflare.com/built-with)


## Development

Built with Workers is a [Gatsby](https://www.gatsbyjs.org/) site.

So as a prerequisite you’ll want to make sure you have the Gatsby CLI installed:

```
npm install -g gatsby-cli
```

Then install this project’s dependencies:

```
npm install
```

Finally, run this command to start a local web server and file watcher:

```
gatsby develop
```

Now you can view the site here:

```
http://localhost:8000/built-with
```

If you do have something running on 8000, Gatsby will increment it (to 8001, 8002, ...) until it finds an available port.

### iPhone / Android development

The normal `gatsby develop` does not expose the local web server to other devices on the network.

So if you need to test on other devices on the same network, e.g. to do iPhone browser testing, you can add the `-H` flag, like this:

```
gatsby develop -H 0.0.0.0
```

### 404 page testing

To test the custom 404 page, visit the site at:

```
http://localhost:8000/built-with/404
```

(Same caveat with the port as above.)

This will present you with a Gatsby-generated page.

Click the button at the top that says “Preview custom 404 page”.


## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
