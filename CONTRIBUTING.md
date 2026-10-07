## What should be filtered

This repository categorizes filters between two files: a main list `GenAI-Blocklist.txt` and an extra list `GenAI-Blocklist-Extra.txt`.

### Items to hide in the main filters
* AI generated summaries of search results, user reviews, articles, or videos.
* Buttons and banners promoting generative AI features on sites/pages where generative AI features are not the primary focus
* Chatbots powered by generative AI that have no option to contact a human for support.
* Videos, images, and stories labeled as AI generated on content hosting sites like DeviantArt, Pixiv, or AO3.
* Social media posts labeled as AI generated.
* Automatically generated video dubs.
* Avoid filtering items that impact core site functionality or have non-AI related functionality.

### Items to hide in the extra filters
* AI chatbots that have an option to contact human support agents.
* Filters that have a chance of blocking non-ai generated content
* Filters that have a chance of breaking site functionality

### Items that should not be hidden
* Any features that impact core site functionality
* Automatic video subtitles that are not explicitly labeled as AI generated. (See https://github.com/Stevoisiak/Stevos-AI-Blocklist/issues/92#issuecomment-4604071069)
* Automated chatbots with pre-written responses that do not use generative AI.
* Search engine results from sites with AI generated images. (Covered by [just_a_husk's image-search Blocklist](https://codeberg.org/just_a_husk/uBlockOrigin-AI-Blocklist) and [laylavish’s AI blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist))
* Full site blocks for AI content farms (Covered by [AI uBlock Origin Blacklist](https://github.com/alvi-se/ai-ublock-blacklist))

## How should filters be written?

* Filters are grouped by site name in alphabetical order.
* NSFW sites have their own separate section below SFW sites. Each one is labeled (NSFW) in the site name.
* Within each site group, filters are grouped by a URL showing where the filter applies. Whenever possible, users should be able to visit the link as-is to see the elements being filtered.
* Filters should include specific identifying elements avoid accidental filtering of unintended items.

## Resources for learning to create filters

Most filter rules in this list use CSS selectors to select AI elements to hide. This type of rule is known as a cosmetic rule or an element hiding filter. To borrow an image from [AdGuard's filter guide](https://adguard.com/kb/general/ad-filtering/create-own-filters/#cosmetic-rule):

<img width="562" height="295" alt="image" src="https://github.com/user-attachments/assets/ca1318a0-e975-4ab7-be8c-a8b0e29921dc" />

For more information on creating cosmetic CSS rules, refer to the following guides:

* [Mozilla - Basic CSS selectors](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Basic_selectors)
* [AdGuard - How to create your own ad filters (cosmetic rule)](https://adguard.com/kb/general/ad-filtering/create-own-filters/#cosmetic-rule)

For more advanced filtering, the following resources may also help.

* [AdGuard Scriptlets and Redirect Resources](https://github.com/AdguardTeam/Scriptlets/tree/master#adguard-scriptlets-and-redirect-resources)
* [uBlock Origin - Resources Library](https://github.com/gorhill/ublock/wiki/Resources-Library)

## How should commit messages/pull requests be written?
 Commit messages should begin with a prefix indicating the type of change being made, followed by the site where the unblocked item appears and a description of the change.

The prefixes are:
* A: Added a new filter
* M: Modified an existing filter
* R: Removed a filter
* C: Cosmetic "meta" change like editing comments or rearranging filters
* T: Transfer filter between extra and main list.

Additionally, if the altered change only applies to the extra filters, it should begin with a +.

## AI Policy

Do not use any form of generative AI when contributing to this repository. This includes using content from a generative AI tool as reference or for finding information.
