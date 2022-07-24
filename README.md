# Unreal Engine Marketplace Additional Asset Filters User Script
[![License](https://img.shields.io/github/license/Drakmyth/remove-highlight-text-fragment)](https://github.com/Drakmyth/remove-highlight-text-fragment/blob/master/LICENSE.md)

A Tampermonkey userscript to automatically remove highlight fragments from Google/Bing search results

Starting in Chromium 80, Google started tacking text fragments on the end of search result urls. When you visit one of the results, your browser will auto-scroll to the location of the text in the fragment and highlight it. This behavior is incredibly obnoxious, but there is no way to disable it.

There are some browser extensions that are able to counteract this behavior, but they do so via a whitelist of domains which doesn't cover all scenarios.

This script will inspect the page url when you visit it and will automatically remove the highlight fragment if it exists and refresh the page to prevent the highlight and scroll before it ever happens.

Issues
--------------------
If you come across something that seems like a bug, please report it here. Make sure to follow these guidelines to ensure your report isn't closed as "Invalid":

* Make sure you are using the latest Release version of the script. Old versions of the script are unsupported. Features and fixes will not be backported to old versions.
* Search to see if someone else has already reported the bug. Duplicate reports just slow down getting things fixed.
* Include steps to reproduce the issue in your report. Screenshots or videos may also prove helpful.

Feature Requests
----------------
Have an idea for other features that would fit well in this script? Awesome! File an issue and detail your idea. Keep it succinct and on-point, and only one feature per request, or it will be closed as "Invalid". Then we'll discuss your idea some and decide whether to implement it or not.

Contributions
-------------
This script is open source! That means if you'd like to try your hand at fixing a bug or implementing a feature, please do so! Head over to the Issues page and look for any open issues tagged with the "Accepted" label. Create a branch, work on it, then submit a pull request. We'll work together to iron out any concerns with your code, and then we'll merge it in and your code will become a part of this script's legacy!

License
-------
remove-highlight-text-fragment.user.js is licensed under the MIT License (MIT). See [LICENSE](./LICENSE.md) for details.
