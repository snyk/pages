---
title: Tracking and Analytics
date-modified: 21st June 2016
---

Our CLI tool reports an event for each command to our analytics, including the version of the CLI tool, the User ID, and the package name. This allows us to better understand how the CLI client is used, and informs our product development decisions.

If you would like to opt out, you can do so by running the following command:

```
snyk config set disable-analytics=1
```

To remove the flag, run:

```
snyk config unset disable-analytics
```

If you have any questions or problems, please email us.
