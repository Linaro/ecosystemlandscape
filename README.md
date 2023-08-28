# Linaro Arm Ecosystem Landscape Jekyll Site

This is the git repository for the [https://ecosystemlandscape.linaro.org](https://ecosystemdashboard.linaro.org/) static Jekyll-based website.

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

The built web site directory will be [https://production.ecosystemdashboard.linaro.org](https://production.ecosystemdashboard.linaro.org).

For more information, please see the [build container wiki](https://github.com/linaro-its/jekyll-build-container/wiki) and the [link checker wiki](https://github.com/linaro-its/jekyll-link-checker/wiki).

## Rules to add a new project to the top level

The project can be added to the top level if it can fit the one of the following conditions:

1. The project officially released Arm supported releases.

2. The project itself does not release Arm supported releases(some project only release source code), but they officially claimed that they can run on.

3. The project neither released Arm supported releases, nor officially claimed to have Arm support, but some of the mainstream OS distribution provided packages(CentOS, Ubuntu, openEuler, etc), we can probably also provide the information, because those OS distributions can provide support for the software.

## Pull Requests

When a Pull Request is created, GitHub Actions are used to automatically build a test version of the proposed modified site and then check that any links in the pages are valid.

If there are any questions or problems with the GitHub Actions, please contact [Linaro IT Services](https://servicedesk.linaro.org/servicedesk/customer/portal/3/create/50).

## Project Details Structure

Directory "_post" contains all the sub-page info using yaml, so please refer to existing files to filling in the content.

| Field | Details|
|-------| ------ |
|category*|Filling the category filed, e.g. "storage", "database", "big data" |
|project - type* | Coding language of the project |
|project - logo* | Better to find the png logo without any background. Store it at assets/images/projects/storage |
|project - overview* | Project introduction |
|support_release* | All support arm64 release |
|user_stories(if have) - optional | The user stories, please check with user before public the cases. Reference to [Hadoop User story][1] |
|work_items | Patch, PR, Jira Items which is related to this project support and status on Arm64, the status can be DONE, TODO or WIP |
|Events - optional | All the presentations, talks, demo which is related to this project support and status on Arm64 |

\* required field

** offer a “not available” option so we can flag it.

[1]: https://github.com/Linaro/ecosystemlandscape/blob/main/_posts/2021-08-31-ApacheHadoop.md?plain=1#L32



