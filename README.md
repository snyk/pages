![Snyk logo](https://snyk.io/style/asset/logo/snyk-print.svg)

***

# Pages

Most of the site is hosted on the Registry repo, but for pages that are mainly content, we host them here so they are quicker and easier to edit. Akamai looks at the page here, and sets the page's url to be under the main domain so it appears as though it is in Registry.

**Currently, any changes you make will immediately be pushed to production if the page is being served by Akamai. Please test your changes locally before commiting to the main branch (`gh-pages`).**

| [![](https://github.com/Snyk/general/blob/master/assets/internal-icons/manual.png?raw=true)](https://github.com/Snyk/pages/wiki) | [Pages documentation](https://github.com/Snyk/pages/wiki) |
| ------------- | ------------- |

## Usage

Check out the [Markdown-cheatsheet](https://github.com/Snyk/general/wiki/Markdown-cheatsheet) for how to write content.

## How to test

## Notes and caveats

In order to pull in updated assets from `@snyk/snyk-ui`, run `npm install` and commit the changed assets.
