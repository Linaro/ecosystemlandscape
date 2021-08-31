# Linaro Arm Ecosystem Landscape Jekyll Site

This is the git repository for the ecosystemlandscape.linaro.org static Jekyll-based website.

Hosted in this repo are the markdown content files associated with the website. Feel free to [submit a PR](https://github.com/Linaro/ecosystemlandscape/pulls) / [Issue](https://github.com/Linaro/ecosystemlandscape/issues/new) if there is anything you would like to change.

This static Jekyll site is using the [`linaro-jekyll-theme`](https://github.com/linaro-marketing/linaro-jekyll-theme). Please take a moment to review the guides on the [theme's GitHub wiki](https://github.com/linaro-marketing/linaro-jekyll-theme/wiki).

---

## Contributing

To make it easier to contribute to the content, Linaro provides a couple of Docker containers for building and checking the site. All you need is Docker installed on your computer and enough RAM and disc space.

To build the site:

```bash
cd <git repository directory>
./build-site.sh
```

To build the site and then serve it so that you can check your contribution appears:

```bash
cd <git repository directory>
JEKYLL_ACTION="serve" ./build-site.sh
```

To check that your contribution doesn't include any broken links:

```bash
cd <built web site directory>
../check-links.sh
```

The built web site directory will be `production.ecosystemlandscape.linaro.org`.

For more information, please see the [build container wiki](https://github.com/linaro-its/jekyll-build-container/wiki) and the [link checker wiki](https://github.com/linaro-its/jekyll-link-checker/wiki).

## Pull Requests

When a Pull Request is created, GitHub Actions are used to automatically build a test version of the proposed modified site and then check that any links in the pages are valid.

If there are any questions or problems with the GitHub Actions, please contact [Linaro IT Services](https://servicedesk.linaro.org/servicedesk/customer/portal/3/create/50).
