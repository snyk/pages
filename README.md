## How this works

Most of the site is hosted on the Registry repo, but for pages that are mainly content, we host them here so they are quicker and easier to edit. Akamai looks at the page here, and sets the page's url to be under the main domain so it appears as though it is in Registry.

**Currently, any changes you make will immediately be pushed to production if the page is being served by Akamai. Please test your changes locally before commiting to the main branch (`gh-pages`).**

## Setting up the repo locally

If you want to make changes and view them locally, you'll need to do the following:

1. Clone the repo
2. In the command line, navigate to the repo's folder and run `bundle install`
3. If there are no errors, run `jekyll serve`
4. Go to **http://localhost:4000/** in your browser

Once you've done this, any time you want to run the repo again, follow these steps again, skipping step 1.

## Writing content

When you edit the YAML front-matter on a page, make sure your text is wrapped in double quote marks, like this:

```
title: "Dependencies make your app vulnerable."
```

This will prevent the text from breaking if you use a colon, or a line break.

### Homepage

Where to edit content: https://github.com/Snyk/pages/blob/gh-pages/homepage.html

### Pricing

Where to edit content: https://github.com/Snyk/pages/blob/gh-pages/pricing.html

Where to edit the FAQs:
https://github.com/Snyk/pages/tree/gh-pages/_faqs

### Features

Where to edit content: https://github.com/Snyk/pages/blob/gh-pages/features.html

Individual features content:
https://github.com/Snyk/pages/tree/gh-pages/_features

### Policies

Where to edit sections:
https://github.com/Snyk/pages/tree/gh-pages/_policies

## Editing the HTML

If you need to make changes to the entire structure of the page, the various layouts live in the `_layouts` folder: https://github.com/Snyk/pages/tree/gh-pages/_layouts

The includes (partials) live here: https://github.com/Snyk/pages/tree/gh-pages/_includes
