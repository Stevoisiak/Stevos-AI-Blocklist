# Stevo's AI Blocklist

A filter list for [uBlock Origin](https://github.com/gorhill/uBlock?tab=readme-ov-file#ublock-origin-ubo) and [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html) that hides specific website features which use Generative AI and content labeled as AI-Generated.

Available for PC/Linux ([Firefox](#firefox-or-microsoft-edge), [Edge](#firefox-or-microsoft-edge), [Chrome](#google-chrome-desktop), [Brave](#brave-desktop)), macOS ([Firefox](#firefox-or-microsoft-edge), [Edge](#firefox-or-microsoft-edge), [Chrome](#google-chrome-desktop), [Safari](#safari-macos)), Android ([Firefox](#firefox-android)), and iOS/iPadOS ([Safari](#safari-iosipados), [Brave](#brave-browser-iosipados)).

## Examples of filtered content
* Google's AI Overviews
* YouTube's Ask button, video summaries, auto-dubbing, and 'Super Resolution' upscaling
* Copilot buttons on GitHub, Bing, Microsoft 365, and Azure Portal
* Pixiv and DeviantArt images with AI-generated label
* Amazon Rufus's product and review summaries
* Reddit Answers and recommended posts from AI subreddits
* Facebook's AI chat
* TikTok videos tagged as AI-generated
* X/Twitter's Grok buttons, posts from Grok, and posts with "made with AI" label

## Image comparison

Before:

<img width="687" height="538" alt="Google homepage with AI" src="https://github.com/user-attachments/assets/248231e3-a107-40a5-a757-b5255decdc19" />

After:

<img width="687" height="359" alt="Google homepage without AI" src="https://github.com/user-attachments/assets/e9c84390-6702-4d9e-9e01-c18f4893c5fe" />

## Installation
### Firefox or Microsoft Edge
1. Install [uBlock Origin](https://github.com/gorhill/ublock#ublock-origin-ubo).
2. Left-click [this link](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt&title=Stevo's%20AI%20Blocklist).
3. Press "_Subscribe_" to import the filter list.

If the above instructions didn't work, (possibly due to multiple adblockers being installed), you can try importing manually:

1. Install [uBlock Origin](https://github.com/gorhill/ublock#ublock-origin-ubo).
2. Click the uBlock button in the toolbar and open Dashboard Settings (gear icon)
3. Select the "_Filter lists_" tab
4. Open the "_Import..._" section and paste [`https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt)
5. Click "_Apply Changes_"

### Google Chrome (Desktop)
1. Install [AdGuard AdBlocker](https://chromewebstore.google.com/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg) for Chrome.
2. Click the green AdGuard icon in Chrome then click the gear icon.
3. Open the Filters tab, go to "Custom", and click the "extension settings" link.
4. Enable "Allow User Scripts".
5. Return to this page and left-click [this link](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt&title=Stevo's%20AI%20Blocklist).
6. Under "Add custom filter", hit "Next".
    - (_Recommended_) Check the "Trusted" box.
7. Click "Add".

### Safari (macOS)
1. Install [AdGuard Mini](https://adguard.com/en/download-extension/safari.html). ([Instructions](https://adguard.com/kb/adguard-mini-for-mac/installation/))
2. Open AdGuard Mini, accept the EULA, then click _Continue_.
3. Click "_Open Settings_" to open Safari settings.
4. Enable the checkboxes for all seven AdGuard extensions.
     - (Optional) Enable "Allow in Private Browsing"
5. Click the "AdGuard for Safari" extension, and click "*Always Allow on Every Website...*"
6. In the notification that appears, click "*Always Allow on Every Website...*" again.
7. Open the AdGuard Mini app and go to *Settings → Filters → Custom filters*
8. Paste the URL [`https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt)
9. Click *Next → Add*
10. Change the toggle for custom filters from "Disabled" to "Enabled"

### Brave (Desktop)
1. Open _Settings → Extensions → Manifest V2 extensions_.
2. Toggle "_Enable uBlock Origin_" to On.
3. Left-click [this link](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt&title=Stevo's%20AI%20Blocklist).
4. Press "_Subscribe_" to import the filter list.

### Firefox (Android)
1. Open Firefox
2. Tap the action menu (⋮) and select "_Extensions_"
3. Click the plus (+) next to _uBlock Origin_ and install it
4. Close and reopen the _Extensions_ menu
5. Tap _uBlock Origin_ and select _Settings_
6. Open the "_Filter lists_" tab
7. Scroll to the bottom and tap "_Import..._"
8. Paste in the link [`https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt)
9. Tap "_Apply Changes_"

### Safari (iOS/iPadOS)
1. Install [AdGuard Ad Blocker for Safari](https://apps.apple.com/us/app/adguard-ad-blocker-for-safari/id1047223162)
2. From your home screen, open *Settings → Apps → Safari → Extensions*
3. Tap each "AdGuard" extension and enable *Allow Extension*.
   - (Optional) Enable "_Allow in Private Browsing_"
4. Tap the first "Adguard" extension, scroll down and change "All websites" to "Allow". 
5. Open the *AdGuard* app and go through initial setup
6. Tap the shield icon to open the Protection screen
7. Tap *Safari Protection → Filters → Custom* (Tap the text itself, not the on-off icon)
8. Tap "*Add a filter*"
9. Paste the URL [`https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt)
10. Tap *Next → Add*.
11. Change the toggle for custom filters from "Disabled" to "Enabled"

### Brave Browser (iOS/iPadOS)
1. Install [Brave Browser](https://apps.apple.com/us/app/brave-browser-search-engine/id1052879175).
2. Open Brave and tap *... → Shields and Privacy → Content Filtering → Add Filter by URL...*
3. Paste in the URL [`https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist.txt)
4. Press *Add*.

## Optional extra blocklist
There is an additional optional filter list [`GenAI-Blocklist-Extra.txt`](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist-Extra.txt) with additional filters that are more subjective or experimental. They may be more prone to accidentally blocking non-AI content or breaking site functionality. These include:
* AI category in headers on news sites.
* Customer support chatbots that must be used before you can contact human customer support.
* YouTube: Trusted filter to remove autodubbing when loading a video directly via URL, but causes visible page refresh even on videos without autodubbing.
* Zoom: Highlights and automatic chapters on recorded meetings.
* Early versions of filters that require testing

## FAQ
### Which adblockers will this filter list work with?
These filters were developed for [uBlock Origin](https://github.com/gorhill/ublock#ublock-origin-ubo) and [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html). You should also be able to use them with [AdBlock](https://getadblock.com/), [Adblock Plus](https://adblockplus.org/), or [Brave's](https://brave.com) integrated adblocker, but issues may occur as these are not fully supported.

### Will this remove sites that post AI generated content from search results?
No. If you want to block AI sites from search engines, try [laylavish's Huge AI Blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist).

### Can I use these filters with [Pi-hole](https://pi-hole.net/)?
No. Pi-hole and uBlock Origin work differently. uBlock Origin allows filtering individual elements on pages, while Pi-hole blocks entire domains.

### Can I use these filters with [Opera](https://www.opera.com/)?
No. These filters do not work with Opera's built-in adblocker or uBlock Origin for Opera. The built-in adblocker doesn't allow importing custom filter lists via URL while uBlock Origin for Opera didn't filter correctly when testing. ([This may be an issue with Opera](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/issues/64))

### How many websites have filters for AI features?
Over 300.

### Why are AI Overviews still showing up on Google?
If you use AdBlock Plus, make sure "[Show acceptable ads](https://help.adblockplus.org/adblock-plus-help-center/what-are-acceptable-ads)" is [disabled in your settings](https://help.adblockplus.org/adblock-plus-help-center/block-all-ads).

### Why is AdGuard recommended for Google Chrome and iOS instead of uBlock Origin?
uBlock Origin is not available for Google Chrome and iOS.

While uBlock Origin Lite exists as an alternative, it [does not support custom filter lists on iOS](https://github.com/uBlockOrigin/uBOL-home/issues/167#issuecomment-4928293779). Support [was added in uBO Lite for Chrome](https://github.com/uBlockOrigin/uBOL-home/issues/167#issuecomment-4753728166), but compatibility with this filterlist has not been thoroughly tested. A previous version of this README suggested copying the GenAI filters into uBO Lite's custom filters as a workaround. However, filtering was unreliable, updating required [manually deleting the old filter rules](https://superuser.com/q/1934748/358766), and some filter rules were incompatible.

### Will this prevent AI summaries from being generated in the background?
Sometimes. This filter list was created with the primary goal of hiding AI elements, but some network filters have been added to prevent content generation.

### Where can I find a full list of filtered items?
Check [`GenAI-Blocklist.txt`](https://github.com/Stevoisiak/Stevos-AI-Blocklist/blob/main/GenAI-Blocklist.txt) and [`GenAI-Blocklist-Extra.txt`](https://github.com/Stevoisiak/Stevos-AI-Blocklist/blob/main/GenAI-Blocklist-Extra.txt).

### Why are trusted filters recommended in AdGuard but not uBlock Origin?
Some filters use [scriptlets](https://github.com/AdguardTeam/Scriptlets/blob/master/wiki/about-scriptlets.md) to block AI items. (DeviantArt & Pixiv image filters, YouTube autodubbing, TikTok videos, etc). Unlike uBlock Origin, AdGuard [requires trusted filters for all scriptlets](https://github.com/AdguardTeam/AdguardBrowserExtension/issues/3522#issuecomment-4441812031). Additionally, enabling trusted filters is easier in AdGuard compared to uBlock Origin.

### Why do some filters show "*Invalid filter: Filter requires trusted source*" in uBlock Origin?
A small number of filters require trusted filters in uBlock Origin. Trusted filters are disabled by default in uBlock Origin for security reasons, as they allow directly executing code on webpages.

To be clear, ***if you use uBlock Origin, you do not need to mark this list as trusted to use a majority of the AI filters***. However, if you do want these extra filters, you can go to [uBlock Origin's advanced settings](https://github.com/gorhill/ublock/wiki/Advanced-settings) and add `https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/` to [`trustedListPrefixes`](https://github.com/gorhill/ublock/wiki/Advanced-settings#trustedListPrefixes).

### Why do YouTube videos still sometimes play AI dubbed audio tracks?
The filter for automatic dubbing on YouTube does not work when opening a video via direct URL. (IE: Entering the address directly in your browser's URL bar). It will work when clicking a video while already on YouTube, such as on YouTube's homepage, search results, or suggested videos.

The [extra filter list](https://raw.githubusercontent.com/Stevoisiak/Stevos-AI-Blocklist/refs/heads/main/GenAI-Blocklist-Extra.txt) has a filter that works when loading directly from URL, but it requires allowing trusted filters to run, ([see above FAQ entry](#why-do-some-filters-show-invalid-filter-filter-requires-trusted-source-in-ublock-origin)), and causes a visible page refresh whenever a video is loaded directly via URL.

### Ads are appearing on YouTube after adding this filter
This was a [known issue](https://github.com/Stevoisiak/Stevos-AI-Blocklist/issues/110) when using the AI Blocklist with Brave that [should be resolved](https://github.com/brave/adblock-rust/issues/679#issuecomment-4869440121). If you are still seeing YouTube ads and have confirmed it *only* occurs when the AI blocklist is installed, please [open an issue](https://github.com/Stevoisiak/Stevos-AI-Blocklist/issues).

## Contributing guidelines
If you want to [report an issue](https://github.com/Stevoisiak/Stevos-AI-Blocklist/issues) or submit a pull request for an item that isn't being blocked, please include the URL where the unblocked item appears and a screenshot of the page showing the unblocked item.

Commit messages use prefixes to indicate the type of change.
* A: Added a new filter
* M: Modified an existing filter
* R: Removed a filter
* C: Cosmetic "meta" change like editing comments or rearranging filters
* F: Fixed a filter (not working, blocking too much, typo, etc.)
* +: Filter applied to the "extra" list

## Other AI blocking tools
### General
* [Just the Browser](https://justthebrowser.com/): Removes AI features, telemetry, and sponsored content from web browsers.
* [RemoveWindowsAI](https://github.com/zoicware/RemoveWindowsAI): Removes AI components in Windows.
* [uBlockOrigin Huge AI Blocklist](https://codeberg.org/just_a_husk/uBlockOrigin-AI-Blocklist): Filter list to remove sites with AI generated content from search engines.
* [AI uBlock Origin Blacklist](https://github.com/alvi-se/ai-ublock-blacklist): uBlock Origin filter list for AI content farms. 
* [Fanboy's Anti-AI Suggestion List](https://github.com/easylist/easylist/blob/master/fanboy-addon/fanboy_ai_suggestions.txt): Another uBlock Origin filter list aimed at AI widgets. Used as a reference for a few of the filters on this list.
* [Firewalla's NSFW AI Blocklist](https://github.com/firewalla/fw-public-lists/blob/main/nsfw-ai.txt): Blocklist of adult-focused AI chatbots.

### Media 
* YouTube
  * Blocktube ([Chrome/Edge](https://chromewebstore.google.com/detail/blocktube/bbeaicapbccfllodepmimpkgecanonai?hl=en-US), [Firefox](http://addons.mozilla.org/en-US/firefox/addon/blocktube/)): Extension for blocking channels and videos on YouTube.
    * [Blocklist for AI music on YouTube](https://surasshu.com/blocklist-for-ai-music-on-youtube/): List of AI music channels for Blocktube.
    * [Ionotter's YT Blocklist](https://pastebin.com/QS93tnXk): List of channels that use AI for BlockTube.
  * [CevvalYoutubeAIBlocklist](https://github.com/cevvalkoala/CevvalYoutubeAIBlocklist): Filter list for AI Music channels on YouTube for uBlock Origin.
* Spotify
  * [Spotify AI Band Blocker](https://github.com/Reginald-Gillespie/Spotify-AI-Band-Blocker): Plugin for Spicetify to block AI artists on Spotify.
  * [Spotify AI Blocker](https://github.com/CennoxX/spotify-ai-blocker): Userscript to block AI artists on Spotify.
* [AI warning for Steam](https://github.com/seeeeew/aiwarningforsteam): Browser extension to blur or hide Steam games with an AI content disclosure.

### Website admin tools
* [Anubis](https://github.com/techaroHQ/anubis): Web firewall for blocking requests from AI companies.
* [ai.robots.txt](https://github.com/ai-robots-txt/ai.robots.txt): List of AI crawlers to block as a website owner.

## Feedback
If you want to report an AI widget that is unblocked, please [submit an issue](https://github.com/Stevoisiak/Stevos-AI-Blocklist/issues) and include the website URL and a screenshot of the unblocked item. 

If you have any feedback about this project, I can be reached on Bluesky at [@stevoisiak.bsky.social](https://bsky.app/profile/stevoisiak.bsky.social) or via email at Stevoisiak(at)gmail.com.
