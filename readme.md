# [Search Engine Optimization (SEO)](//marcobiedermann.github.io/search-engine-optimization/)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](//github.com/sindresorhus/awesome)
[![Join the chat at https://gitter.im/marcobiedermann/search-engine-optimization](https://badges.gitter.im/Join%20Chat.svg)](//gitter.im/marcobiedermann/search-engine-optimization?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A helpful checklist / collection of Search Engine Optimization (SEO) tips and technics.

## Table of Contents
* [URL](#url)
* [Accessibility](#accessibility)
* [Meta Information](#meta-information)
* [Keywords](#keywords)
* [Content](#content)
* [Images](#images)
* [Videos](#videos)
* [Links](#links)
* [Mobile](#mobile)
* [Sitemap](#sitemap)
* [Social Media](#social-media)
* [Tools & Services](#tools--services)
  * [Webmasters](#webmasters)
  * [Analytics](#analytics)
  * [Optimization](#optimization)
  * [Keywords](#keywords-1)
  * [Structured Data](#structured-data)
  * [Bookmarklets](#bookmarklets)
* [Books](#books)
* [Courses](#courses)

## URL
* **Descriptive URLs:** use a descriptive page url, which should reflect your targeted keyword
* **[Subdomain or subfolder](//www.youtube.com/watch?v=_MswMYk05tk):** subdomains are seen as separate domains
* **[Hyphens](//www.youtube.com/watch?v=AQcSFsQyct8):** split words using hyphens
* **[www or no-www](//support.google.com/webmasters/answer/44231):** provide both domains, but set a prefered version in Google Webmaster Tools
* **[Localisation](//support.google.com/webmasters/answer/62399):** choose a country-specific domain, for better local search results
* **[HTTPS](//googlewebmastercentral.blogspot.be/2014/08/https-as-ranking-signal.html):** Security is a top priority for Google
* **[URL builder](//support.google.com/analytics/answer/1033867):** Use this tool to add custom compaign parameters to your URLs
* **[File extension](//www.youtube.com/watch?v=dSG6C33GwsE)**: do not strip out the file extension on URLs

## Accessibility
* **403:** provide a 403 - Access denied page
* **404:** provide a 404 - Page not found page
* **Robots:** block pages which should not be indexed via the `robots.txt` file or
`<meta name="robots" content="">`
* **File not found:** avoid `404 FILE_NOT_FOUND` errors
* **Redirects:** Avoid redirects if possible. Use 301 redirect instead of 302
* **[Pagination](//support.google.com/webmasters/answer/1663744):** implement the `rel="next"` and `rel="prev"` attributes to links
* **Moving a website:** redirect all your links to the new location via `.htaccess`
* **[Performance](//developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/slow-mobile-pages):** performance and loading time is important
* **Validation:** write valid code ([HTML Validator](//validator.w3.org/) [CSS Validator](//jigsaw.w3.org/css-validator/))
* **[WAI-Aria](//www.w3.org/TR/wai-aria/):** use WAI-Aria tags to help machines understanding your code
* **[RichSnippets](//schema.org/):** markup your code with rich snippets, they show up on the search results page
* **[Custom Search](//developers.google.com/structured-data/slsb-overview):** with sitelink Google Sitelink search box, people can reach your content more quickly
* **Layout:** Use `divs` instead of `tables` for layout. Using `tables` is semantically not correct.

## Meta Information
* **Title:** each page should have a unique speaking title (60 - 100 characters)
`<title>Website Title</title>`
* **[Description](//www.youtube.com/watch?v=W4gr88oHb-k):** each page should have a unique description (max. 160 characters)
`<meta name="description" content="">`

## Keywords
* **Single:** every page should have a single unique targeted keyword
* **Research:** rank for keywords with high traffic and less competition
* **[URL](//www.youtube.com/watch?v=rAWFv43qubI):** keyword should appear in URL name
* **Title:** keyword should appear in page title
* **Heading:** keyword should appear in headings
* **Content:** keyword should apear in ~3% of article length
* **[Meta Tag](//www.youtube.com/watch?v=jK7IPbnmvVU):** you can ommit the `<meta name="keywords" content="">`,
search engines do not use this meta tag

## Content
* **Content:** Content matters the most in SEO
* **Headings:** Clear structure `H1` -` H6` max. 70 characters long
* **Strong:** use `strong` tag to highlight your targeted keyword
* **[Uniqueness](//www.youtube.com/watch?v=mQZY7EmjbMA):** do not provide duplicated content, use unique content types
* **Length:** article should be at least 300 words
* **Freshness:** new content is important. Updating pages or regulary posting is recommended
* **Flash:** avoid Flash content and flash pages. They are not accessible on mobile phones and will be ranked lower

## Images
* **[File name](//www.youtube.com/watch?v=h2SWuUobbr0):** use a short descriptive name
* **[Alt tag](//support.google.com/webmasters/answer/114016):** add an alt-tag this a description of the image (60 - 70 characters)
* **Dimentions:** add the `width=""` and `height=""` attributes to the image
* **[Responsive Images](//www.w3.org/TR/html-picture-element/):** serve the most optimized image corresponding to the window size
* **Size:** keep the filesize as low as possible
* **[Optimization](//imageoptim.com/):** Optimize images by removing some meta information

## Videos
* **Controls:** Add controls to playback and control your video
* **Embed:** Allow others to embed your videos
* **Transcriptions:** use transcriptions for indexing, usability & content
* **[Unplayable content](//developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/unplayable-content):** Avoid unplayable video content. Use HTML5 `<video>` tag instead of Flash

## Links
* **Title:** add the title attribute to links
* **Backlinks:** Only add external links if you got a backlink to your site
* **[nofollow](//support.google.com/webmasters/answer/96569):** add `rel="nofollow"` attribute to external links only to prevent spam and bad links
* **Internal links:** add ~3 internal links to your content
* **Naming:** Use a descriptive link name: “Click here” or “Read more” are bad link text. Better “Read more about SEO and Web Accessibility”

## Mobile
* **Viewport:** tell browsers how to adjust the page's dimension and scaling to suit the device
`<meta name="viewport" content="width=device-width, initial-scale=1">`
* **[mobile friendly](//googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html):** mobile optimized sites are marked in search results. Test for [mobile friendly site](//www.google.com/webmasters/tools/mobile-friendly/)
* **[AppLinks](//applinks.org/documentation/):** apps that link to your content can then use this metadata to deep-link into your app
* **[Tap targets](//developers.google.com/speed/docs/insights/SizeTapTargetsAppropriately):** clickable links should not be too small
* **[Smart App Banner](//developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html):** Safari has a Smart App Banner feature that provides a standardized method of promoting apps on the App Store from a website.

## Sitemap
* **[HTML sitemap](//www.youtube.com/watch?v=hi5DGOu1uA0):** An HTML sitemap allows site visitors to easily navigate a website.
* **[XML sitemap](//support.google.com/webmasters/answer/183668):** Help search engines to index your pages
* **[Image sitemap](//support.google.com/webmasters/answer/178636):** Increase that your images can be found in Image Search results
* **[Video sitemap](//support.google.com/webmasters/answer/80471):** Make sure, search engines know about all the video content on your site
* **[Mobile sitemap](//support.google.com/webmasters/answer/6082207):** For feature phones, you can create a mobile sitemap

## Social Media
* **Social Shares:** provide sharing options for your site
* **[Social Profiles](//developers.google.com/webmasters/structured-data/customize/social-profiles):** add social profiles to your Google search results
* **[OpenGraph](//ogp.me/):** The Open Graph protocol enables any web page to become a rich object in a social graph.
* **[Facebook](//developers.facebook.com/docs/sharing/best-practices):** Sharing Best Practices for Websites & Mobile Apps
* **[Twitter](//dev.twitter.com/cards/getting-started):** with Twitter cards, you can attach photos, videos and media experience to you Tweets
* Authorship information
* **[Google+ Authorship](//www.youtube.com/watch?v=FgFb6Y-UJUI):** add Google+ authorship information to your page
`<link rel="author" href="//plus.google.com/u/0/[GOOGLE+ ID]">`  or
`<a href="//plus.google.com/u/0/[GOOGLE+ ID]" rel=author">Google+ Profile</a>` or
`<a href="//plus.google.com/u/0/[GOOGLE+ ID]" rel=me">Google+ Profile</a>` or
`<a href="//plus.google.com/u/0/[GOOGLE+ ID]" rel=publisher">Google+ Profile</a>`

## Tools & Services

### Webmasters
* **[Bing Webmasters](//www.bing.com/toolbox/webmaster):** allows webmasters to add their websites to the Bing index crawler.
* **[Google Search Console (GWT)](//www.google.com/webmasters/):** allows webmasters to check indexing status and optimize visibility ot their websites
* **[Google Tag Manager](https://www.google.com/analytics/tag-manager/):** Learn about Google Analytics Tag Manager and how it can help simplify your life and need for IT requests. Launch new tags with a few clicks.

### Analytics
* **[Google Analytics](//www.google.com/analytics/):** generate detailed statistics about a website's traffic
* **[Piwik](//piwik.org/):** is an open analytics platform
* **[Yahoo Web Analytics](//web.analytics.yahoo.com):** is Yahoo!’s alternative to the dominant Google Analytics.

### Optimization
* **[PageSpeed Insights](//developers.google.com/speed/pagespeed/insights/):** Page Speed Insights measures the performance of a page for mobile devices and desktop devices.
* **[Varvy Seo tool](//varvy.com/tools/):** displays: domain strength, links, image seo, social counts & mentions, page/technical seo, pagespeed and more.
* **[Webpagetest.org](//www.webpagetest.org/):** Web Page Test gives you an overall performance waterfall as well as rendering timeline for sites. It also provides critical insight into time to first byte and what could be holding back web page performance

### Keywords
* **[AdWords Keyword Tool](//adwords.google.com/KeywordPlanner):** plan your Search Network campaigns and learn what your customers are looking for
* **[Google Trends](//www.google.com/trends/):** explore Google trending search topics with Google Trends.

### Links
* **[Screaming Frog SEO Spider Tool & Crawler Software](//www.screamingfrog.co.uk/seo-spider/):** The Screaming Frog SEO Spider is a small desktop program (PC or Mac) which crawls websites’ links, images, CSS, script and apps from an SEO perspective.

### Structured Data
* **[Google+ Snippet Creator](//developers.google.com/+/web/snippet/):** customize the snippet people see when your page is shared.
* **[Structured Data Testing Tool](//developers.google.com/structured-data/testing-tool/):** past in you rich snippets or url to test it
* **[Twitter card validator](//cards-dev.twitter.com/validator):** Enter the URL of the page with the meta tags to validate
* **[Facebook Debugger](//developers.facebook.com/tools/debug):** Enter the URL you want to scrape to see how the page's markup appears to Facebook.
* **[Pinterest](//developers.pinterest.com/rich_pins/validator/):** Validate your Rich Pins and apply to get them on Pinterest

### Bookmarklets
* **[OuiSEO](//github.com/carlsednaoui/seo-bookmarklet):** An open-source bookmarklet that shows you on-page SEO and social meta data information.
* **[SEO Bookmarklet](//twkm.ca/projects/seo-bookmarklet):** A One-Stop SEO Bookmarklet to Quickly Review On-Site SEO

## Books
* **[SEO 2016: Learn Search Engine Optimization](//www.amazon.com/dp/1512275069/ref=cm_sw_su_dp):** A Comprehensive Must-Have Guide to SEO in Today's Competitive Search Environment
* **[SEO For Dummies, 6th Edition](//shop.oreilly.com/product/9781119129554.do):** Your fully updated guide to search engine optimization
* **[SEO Warrior](//shop.oreilly.com/product/9780596157081.do):** Essential Techniques for Increasing Web Visibility
* **[Search engine optimization 2016: Learn SEO with smart internet marketing strategies](//www.amazon.com/dp/151534567X/ref=cm_sw_su_dp):** Learn SEO strategies to rank at the top of Google with SEO 2016
* **[The Art of SEO, 3rd Edition](//shop.oreilly.com/product/0636920032908.do):** Mastering Search Engine Optimization

## Courses
* **[ClickMinded Search Engine Optimization Training](//www.udemy.com/seo-training/):** ClickMinded Search Engine Optimization Training with Tommy Griffith by udemy
* **[Ecommerce SEO 101 Video Series](//www.shopify.com/videos/ecommerce-seo-101):** Ecommerce SEO 101 Video Series with Helen Overland by shopify
* **[Learning Search Engine Optimization (SEO): A Video Introduction](//www.video2brain.com/en/courses/learning-search-engine-optimization-seo-a-video-introduction):** Learning Search Engine Optimization (SEO): A Video Introduction with Matt Bailey by video2brain
* **[Learning Web Analytics](//www.video2brain.com/en/courses/learning-web-analytics):** Learning Web Analytics with Matt Bailey by video2brain
* **[SEO Fundamentals](//www.lynda.com/Analytics-tutorials/SEO-Fundamentals/187858-2.html):** SEO Fundamentals with David Booth by Lynda.com
* **[SEO Fundamentals](//www.pluralsight.com/courses/seo-fundamentals):** SEO Fundamentals with Paul Wilson by Pluralsight
* **[SEO Training Course by Moz](//www.udemy.com/whiteboard-seo/):** SEO Training Course with Moz by udemy
* **[SEO for Beginners](//seoforbeginners.com/):** SEO for Beginners: A Video Guide Introduction
* **[SEO for Web Designers](//webdesign.tutsplus.com/courses/seo-for-web-designers):** SEO for Web Designers with Craig Campbell by TutsPlus

## License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](//creativecommons.org/publicdomain/zero/1.0/)
