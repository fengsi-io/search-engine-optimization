# 搜索引擎优化 (SEO)

一份对你有所帮助的搜索引擎优化(SEO)技巧、技术的清单集合。

## 内容

- [网址](#网址)
- [可访问性](#可访问性)
- [Meta 信息](#meta-信息)
- [关键词](#关键词)
- [内容](#内容)
- [图片](#图片)
- [视频](#视频)
- [链接](#链接)
- [移动端](#移动端)
- [站点地图](#站点地图)
- [社媒](#社媒)
- [工具/服务](#工具服务)
  - [站长](#站长)
  - [分析](#分析)
  - [优化](#优化)
  - [关键词](#关键词-1)
  - [链接](#链接-1)
  - [结构化数据](#结构化数据)
  - [书签工具](#书签工具)
  - [浏览器插件](#浏览器插件)
  - [Jekyll 插件](#jekyll-插件)
  - [TYPO3 插件](#typo3-插件)
  - [WordPress 插件](#wordpress-插件)
- [书籍](#书籍)
- [课程](#课程)

## 网址

- 描述性的网址：使用描述性的网址，反应你的目标关键词。
- [文件扩展名](https://www.youtube.com/watch?v=dSG6C33GwsE)：不要去除 url 中的文件扩展名，因为他能反应文件类型.
- [HTTPS](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html)：安全性在 Googel 具有最高优先级。
- [连字符](https://www.youtube.com/watch?v=AQcSFsQyct8)：使用连字符 `-` 分割单词。
- [本地化](https://support.google.com/webmasters/answer/62399)：为了获得更好的本地化搜索结果，可以选择一个该国的本地域名。
- [子域名和子文件夹](https://www.youtube.com/watch?v=_MswMYk05tk)：子域名会被当作单独的域名。
- [网址构建器](https://support.google.com/analytics/answer/1033867)：使用此工具，可在 url 中添加自定义营销活动参数。

## 可访问性

- 403：提供 403 - 禁止访问页面。
- 404：提供 404 - 页面未找到页面。
- [自定义搜索](https://developers.google.com/structured-data/slsb-overview) - 有了 Google Sitelink 搜索框, 大家可以更快的找到你的内容。
- 文件未找到：避免 `404 FILE_NOT_FOUND` 错误.
- 布局：使用 `divs` 而不是 `tables` 来布局。 用 `tables` 在语义上不正确。
- 迁移网站：301 重定向所有的链接到新的地址。
- [分页](https://support.google.com/webmasters/answer/1663744) - 实现链接的 `rel="next"` 和 `rel="prev"` 属性。
- [性能](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/slow-mobile-pages) - 性能和加载时间非常重要。
- 重定向：尽量避免重定向，使用 301 重定向而不是 302。
- [富文本摘要](https://schema.org/) - 在代码中使用富文本摘要，这些会出现在搜索结果中。
- [Robots](https://en.wikipedia.org/wiki/Robots_exclusion_standard) - 使用 `robots.txt` 文件或者
  `<meta name="robots" content="">` 屏蔽不需要索引的页面。
- 验证：编写规范的代码 ([HTML 验证器](https://validator.w3.org/) [CSS 验证器](https://jigsaw.w3.org/css-validator/))。
- [WAI-Aria](https://www.w3.org/TR/wai-aria/) - 使用 WAI-Aria 标记帮助机器理解你的代码。

## Meta 信息

- [描述](https://www.youtube.com/watch?v=W4gr88oHb-k) - 每个页面应有一个唯一的描述（最大 160 个字符）
  `<meta name="description" content="">`。
- 标题：每个页面都要有一个唯一的标题（60 - 100 个字符）`<title>网站标题</title>`。

## 关键词

- 内容：关键词需要站文章长度的 ~3% 。
- 内容标题：关键词应当在内容标题中出现。
- [Meta 标签](https://www.youtube.com/watch?v=jK7IPbnmvVU) - 可以省略 `<meta name="keywords" content="">`，
  搜索引擎已经不适用这个标签了。
- 调查：使用高流量低竞争的关键词做排名。
- 唯一：每个页面都应该有一个唯一的目标关键词。
- 页面标题：关键词应该出现在页面标题中。
- [URL](https://www.youtube.com/watch?v=rAWFv43qubI) - 关键词应当出现在 URL 中.

## 内容

- 内容：内容是 SEO 中最重要的部门。
- Flash：不免使用 Flash 内容和 Flash 页面，这些在移动设备中不能访问，并且排名会更低。
- 新鲜度：新内容很重要。建议定期更新页面或者发布新内容。
- 标题：清晰的 `H1` - `H6`（最大层级）标题结构，最长 70 个字符。
- 长度：至少要有 300 个单词。
- 强调：使用 `strong` 标签强调你的目标关键词。
- [独特性](https://www.youtube.com/watch?v=mQZY7EmjbMA)：不要提供重复的内容，使用唯一的内容类型。

## 图片

- [`alt` 标签](https://support.google.com/webmasters/answer/114016)：使用 `alt` 标签来描述这个图片（60 - 70 个字符）。
- 尺寸：为图片使用 `width=""` 和 `height=""` 属性。
- [文件名](https://www.youtube.com/watch?v=h2SWuUobbr0)：使用一个简短、有描述性的名称。
- [优化](https://imageoptim.com/)：通过移除一些元信息来优化图片。
- [响应式图片](https://www.w3.org/TR/html-picture-element/)：提供窗口大小对应的最优图片。
- 大小：文件大小要尽可能小。

## 视频

- 空间：使用控件来播放和控制视频。
- 可嵌入：允许其他人嵌入你的视频。
- 视频转录：为了可索引、可用性和内容，使用视频转录。
- [无法播放的内容](https://developers.google.com/webmasters/mobile-sites/mobile-seo/common-mistakes/unplayable-content)：避免无法播放的视频内容，使用 HTML5 `<video>` 标签来替代 Flash。

## 链接

- 反链：只有在你的网站有了反向链接后，再添加外部链接。
- 内链：为你的内容添加 3 个左右的内部链接。
- [语言](https://moz.com/learn/seo/hreflang-tag)：`hreflang` 标签让 Google 知道你特定页面使用的是哪一种语言，搜索引擎就可以为使用这种语言搜索的用户提供结果
  `<link rel="alternate" href="example.com/fr/" hreflang="fr-fr" />`.
- 链接文本：使用一个描述性的链接文本：“Click here” or “Read more” 是不好的链接文本，“Read more about SEO and Web Accessibility” 会更好。
- [`nofollow`](https://support.google.com/webmasters/answer/96569)：为外连增加 `rel="nofollow"` 属性只是为了防止垃圾邮件和坏链。
- 标题：为链接添加 `title` 属性。

## 移动端

- [AppLinks](http://applinks.org/documentation/) - 在使用这些元标签后，可以深度链接到链接你内容的应用中。
- [移动端友好]](https://googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html)：移动端优化的网站会在搜索结果中标记出来。[移动端友好站点测试](https://www.google.com/webmasters/tools/mobile-friendly/).
- [智能应用横幅](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html) - Safari 浏览器有智能应用横幅功能，提供了一个在网站上推广 App Store 应用的标准化方法。
- [可点击目标](https://developers.google.com/speed/docs/insights/SizeTapTargetsAppropriately)：可点击的目标不应太小。
- Viewport：告诉浏览器如何调整页面的尺寸和缩放以适应设备。`<meta name="viewport" content="width=device-width, initial-scale=1">`

## 站点地图

- [HTML 站点地图](https://www.youtube.com/watch?v=hi5DGOu1uA0)：HTML 站点地图让访客可以轻松浏览网站。
- [图片站点地图](https://support.google.com/webmasters/answer/178636)：增加你的图片出现在图片搜索结果中的概率。
- [视频站点地图](https://support.google.com/webmasters/answer/80471)：确保搜索引擎知道你网站上的所有视频。
- [XML 站点地图](https://support.google.com/webmasters/answer/183668)：帮助搜索引擎索引你的页面。

## 社媒

- 作者信息。
- [Facebook](https://developers.facebook.com/docs/sharing/best-practices)：分享网站和手机应用的最佳实践。
- [OpenGraph](http://ogp.me/)：开放图协议（The Open Graph protocol）使任何网页成为社交图中的富对象。
- [社媒资料](https://developers.google.com/webmasters/structured-data/customize/social-profiles)：增加搜索社媒资料到 Google 搜索结果中。
- 社会化分享：为网站提供共享选项。
- [Twitter](https://dev.twitter.com/cards/getting-started)：使用 Twitter cards，你可以在你的 Tweet 中附上图片、视频并增强媒体体验。

## 工具/服务

### 站长

- [Bing 站长工具](http://www.bing.com/toolbox/webmaster)：允许站长添加他们的站点到 Bing 索引器。
- [Google Search Console (GWT)](https://www.google.com/webmasters/)：允许站长检查索引状态，并优化可站点的见性。
- [Google Tag Manager](https://www.google.com/analytics/tag-manager/)：了解 Google Tag Manager 以及它如何帮助简化你的工作以及降低 IT 请求，点击几下即可启用新标签。

### 分析

- [Ahrefs](https://ahrefs.com/) - Analyze websites, track social media, build backlinks - Ahrefs has you covered. Try our marketing and SEO tools Site Explorer and Content Explorer today!
- [BuzzSumo](https://app.buzzsumo.com/research/most-shared) - Find the most shared content for any topic or domain.
- [Followerwonk](https://moz.com/followerwonk) - Tools for Twitter Analytics, Bio Search and More.
- [Google Analytics](https://www.google.com/analytics/) - Generate detailed statistics about a website's traffic.
- [Open Site Explorer](https://moz.com/researchtools/ose/) - Use Open Site Explorer to identify link building opportunities. Research backlinks, identify top pages, view social activity, and analyze anchor text.
- [Matomo](https://matomo.org/) - An open analytics platform.
- [SEMrush](https://www.semrush.com/) - SEMrush is a powerful and versatile competitive intelligence suite for online marketing, from SEO and PPC to social media and video advertising research.
- [Seomator](https://seomator.com/) - SEO Audit Tool and website crawler for SEO performance improving with How-to-Fix tips.
- [SEOstats](https://github.com/eyecatchup/SEOstats) - SEOstats is a powerful open source PHP library to request a bunch of SEO relevant metrics.
- [SimilarWeb](https://www.similarweb.com/) - Compare website traffic with SimilarWeb.com's advanced traffic estimator tool. See any website's traffic sources & uncover their online marketing strategies.
- [SpyFu](https://www.spyfu.com/) - Unlimited searches of any competitor's keywords for SEO or Google Ads. Research keywords, and find any domain's strongest content and their most dominant ad copy.
- [Twitter Analytics](https://analytics.twitter.com/) - Measure and boost your impact on Twitter.
- [Plausible](https://plausible.io/) - Simple and privacy-friendly alternative to Google Analytics.

### 优化

- [Web.dev](https://web.dev/) - Get the web's modern capabilities on your own sites and apps with useful guidance and analysis from Web.dev. Whether you already have a website or you're just getting started, learn to build for the modern web at Web.dev.
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Page Speed Insights measures the performance of a page for mobile devices and desktop devices.
- [Varvy Seo tool](https://varvy.com/) - Displays: domain strength, links, image seo, social counts & mentions, page/technical seo, pagespeed and more.
- [Webpagetest.org](https://www.webpagetest.org/) - Web Page Test gives you an overall performance waterfall as well as rendering timeline for sites. It also provides critical insight into time to first byte and what could be holding back web page performance.
- [WooRank](https://www.woorank.com/) - WooRank will help you to address issues on your site & identify opportunities to push you ahead of the competition.
- [Awesometechstack.com](https://awesometechstack.com/) - AwesomeTechStack provides insights into the security, modernity, and performance of any website's technology stack and guidance to improve web vitals and the technology stack.

### 关键词

- [Google Trends](https://www.google.com/trends/) - Explore Google trending search topics with Google Trends.
- [Keyword Planner](https://adwords.google.com/KeywordPlanner) - Plan your Search Network campaigns and learn what your customers are looking for.
- [Keyword Tool](http://keywordtool.io/) - Best FREE alternative to Google Keyword Tool for SEO & PPC keyword research! Get 750+ relevant long-tail keywords from Google Suggest in seconds!
- [Moz Keyword Explorer](https://moz.com/explorer) - Paid Keyword Tool that provides precise search volume, keyword difficulty, SERP Features and organic click through rate data.
- [Keyword Clarity](https://keywordclarity.io) - Free keyword analytics tool that allows you to visualize and group keyword metrics with tree diagrams. The tool works with data from the Google Search Console API and CSVs.
- [SEOwl](https://www.seowl.co) - Track your keyword rankings overtime and monitor your backlinks 

### 链接

- [OpenLinkProfiler](http://www.openlinkprofiler.org/) - Get an in-depth analysis of the freshest live backlinks.
- [Search Engine Spider Simulator](http://tools.seochat.com/tools/search-spider-simulator) - This tool simulates a search engine by displaying the contents of a web page in exactly the way the search engine bot would see it when it crawls the page：See most prominent or inaccessible page elements.
- [Screaming Frog SEO Spider Tool & Crawler Software](https://www.screamingfrog.co.uk/seo-spider/) - The Screaming Frog SEO Spider is a small desktop program (PC or Mac) which crawls websites links, images, CSS, script and apps from an SEO perspective.
- [Linkbuilding Spider](https://github.com/fulldecent/linkbuilding-spider) - A PHP project to check if websites are linking to your website.

### 结构化数据

- [Facebook Debugger](https://developers.facebook.com/tools/debug) - Enter the URL you want to scrape to see how the page's markup appears to Facebook.
- [Pinterest](https://developers.pinterest.com/rich_pins/validator/) - Validate your Rich Pins and apply to get them on Pinterest.
- [Structured Data Testing Tool](https://developers.google.com/structured-data/testing-tool/) - Paste in your rich snippets or url to test it.
- [Twitter card validator](https://cards-dev.twitter.com/validator) - Enter the URL of the page with the meta tags to validate.

### 书签工具

- [OuiSEO](https://github.com/carlsednaoui/seo-bookmarklet) - An open-source bookmarklet that shows you on-page SEO and social meta data information.
- [SEO Bookmarklet](https://twkm.ca/projects/seo-bookmarklet) - A One-Stop SEO Bookmarklet to Quickly Review On-Site SEO.

### 浏览器插件

- [MozBar](https://moz.com/tools/seo-toolbar) - The SEO Toolbar from Moz gives you quick access to many on-page SEO factors, Domain & Page Authority plus a quick nofollow toggle. Download the Free Toolbar today!

### Jekyll 插件

- [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag) - A Jekyll plugin to add metadata tags for search engines and social networks to better index and display your site's content.

### TYPO3 插件

- [Basic SEO Features](https://typo3.org/extensions/repository/view/seo_basics) - Adds a separate field for the title-tag per page, easy and SEO-friendly keywords and description editing in a new module as well as a flexible Google Sitemap.
- [Google sitemap](https://typo3.org/extensions/repository/view/dd_googlesitemap) - High performance Google sitemap implementation that avoids typical errors by other similar extensions.

### WordPress 插件

- [All in One SEO Pack](https://wordpress.org/plugins/all-in-one-seo-pack/) - The most downloaded plugin for WordPress (almost 30 million downloads). Use All in One SEO Pack to automatically optimize your site for Search Engines.
- [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Improve your WordPress SEO：Write better content and have a fully optimized WordPress site using Yoast SEO plugin.
- [Slim SEO](https://wordpress.org/plugins/slim-seo/) - Automated SEO tasks for you with a lightweight WordPress SEO plugin.

## 书籍

- [Search engine optimization 2016：Learn SEO with smart internet marketing strategies](https://www.amazon.com/Search-Optimization-Internet-Marketing-Strategies/dp/151534567X) - Learn SEO strategies to rank at the top of Google with SEO 2016.
- [Search Engine Optimization All-in-One For Dummies](https://www.amazon.com/Search-Engine-Optimization-All-Dummies/dp/1118921755) - Bruce Clay is one of the most respected figures in the SEO community, teaching classes and workshops at all the major conferences. Like the ‘Art of SEO,’ this book is actually pretty technical and probably not your best easy, first guide, despite being part of the ‘Dummies’ series.
- [SEO 2016：Learn Search Engine Optimization](https://www.amazon.com/SEO-2016-Search-Engine-Optimization/dp/1512275069) - A Comprehensive Must-Have Guide to SEO in Today's Competitive Search Environment.
- [SEO Fitness Workbook](https://www.amazon.com/SEO-Fitness-Workbook-2016-Optimization/dp/1518748880) - Step-by-step book on SEO, starting with goals, going through on page SEO such as page tags, and ending up with off page SEO such as link-building and social mentions.
- [SEO For Dummies, 6th Edition](http://shop.oreilly.com/product/9781119129554.do) - Your fully updated guide to search engine optimization.
- [SEO Step-by-Step - The Complete Beginner's Guide to Getting Traffic from Google](https://www.amazon.com/SEO-Step-Step-Complete-Beginners/dp/1497415020) - Also starts with keywords and covers ON PAGE and OFF PAGE SEO. Emphasizes the importance of speed, and has a nice appendix with SEO resources, glossary, and links.
- [SEO Warrior](http://shop.oreilly.com/product/9780596157081.do) - Essential Techniques for Increasing Web Visibility.
- [SEO：Marketing Strategies to Dominate the First Page](https://www.amazon.com/SEO-Marketing-Strategies-analytics-optimization-ebook/dp/B01ACB7LQM) - Introduction to Google Analytics, Webmaster, Website traffic, Adwords, Pay per click, Website promotion and Search engine optimization.
- [The Art of SEO, 3rd Edition](http://shop.oreilly.com/product/0636920032908.do) - Mastering search engine optimization.
- [The Beginner's Guide to SEO](https://moz.com/beginners-guide-to-seo) - New to SEO? Need to polish up your knowledge? The Beginner's Guide to SEO has been read over 3 million times and provides the information you need to get on the road to professional quality SEO.
- [The SEO Battlefield](http://shop.oreilly.com/product/0636920050964.do) - If you want to establish an ongoing SEO program with the goal of increased traffic and search prominence, this practical step-by-step guide will help you understand SEO methodology and then show you how to put those theories into practice.

## 课程

- [Analyzing Your Website to Improve SEO](https://www.lynda.com/Marketing-Small-Business-Marketing-tutorials/Analyzing-Your-Website-Improve-SEO/82409-2.html) - Walks step-by-step through the process of reviewing the content and markup of a web site to improve its ranking in search engine results. With Peter Kent by Lynda.com.
- [ClickMinded](https://www.clickminded.com/) - ClickMinded is an SEO training course for startups that want to grow their organic traffic and sales as quickly as possible.
- [Ecommerce SEO 101 Video Series](https://www.shopify.com/videos/ecommerce-seo-101) - Ecommerce SEO 101 Video Series with Helen Overland by shopify.
- [Improving SEO Using Accessibility Techniques](https://www.lynda.com/HTML-5-tutorials/Improving-SEO-Using-Accessibility-Techniques/89051-6.html) - Make web sites more accessible and search engine friendly through proper markup and web standards compliance. With Morten Rand-Hendriksen by Lynda.com.
- [International SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/International-SEO-Fundamentals/377449-6.html) - Attract international visitors to your websites with these SEO tips. Learn how to determine target markets and optimize your website's technical aspects and content for countries and languages around the world. With David Booth by Lynda.com.
- [Learning Search Engine Optimization (SEO) - A Video Introduction](https://www.video2brain.com/en/courses/learning-search-engine-optimization-seo-a-video-introduction) - Learning Search Engine Optimization (SEO) - A Video Introduction with Matt Bailey by video2brain.
- [Learning Web Analytics](https://www.video2brain.com/en/courses/learning-web-analytics) - Learning Web Analytics with Matt Bailey by video2brain.
- [SEO for Beginners](http://seoforbeginners.com/) - SEO for Beginners: A Video Guide Introduction.
- [SEO for Ecommerce](https://www.lynda.com/Google-Analytics-tutorials/SEO-Ecommerce/386884-2.html) - SEO for ecommerce is different. Get strategies tailored for optimizing an online store to improve page rankings and build traffic. With Steven Harris by Lynda.com.
- [SEO for Local Visibility](https://www.lynda.com/Google-Maps-tutorials/SEO-Local-Visibility/178132-2.html) - Achieve maximum visibility in search rankings with these local SEO strategies. With Brad Batesole by Lynda.com.
- [SEO for Web Designers](https://webdesign.tutsplus.com/courses/seo-for-web-designers) - SEO for Web Designers with Craig Campbell by TutsPlus.
- [SEO Fundamentals](https://www.lynda.com/Analytics-tutorials/SEO-Fundamentals/187858-2.html) - SEO Fundamentals with David Booth by Lynda.com.
- [SEO Fundamentals](https://www.pluralsight.com/courses/seo-fundamentals) - SEO Fundamentals with Paul Wilson by Pluralsight.
- [SEO Tools Fundamentals](https://www.lynda.com/Buzzstream-tutorials/SEO-Tools-Fundamentals/368917-2.html) - Learn about today's top SEO tools for technical optimization, content optimization, offsite optimization, and competitive research. With Brad Batesole by Lynda.com.
- [SEO Training Course by Moz](https://www.udemy.com/whiteboard-seo/) - SEO Training Course with Moz by udemy.
- [SEO: Keyword Strategy in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Keyword-Strategy-Depth/147030-6.html) - Learn how to research keywords, apply them to your website, and create ad campaigns around keywords. Increase your site traffic and better understand your user's intent with keywords. With Matt Bailey by Lynda.com.
- [SEO: Link Building in Depth](https://www.lynda.com/Business-Online-Marketing-tutorials/SEO-Link-Building-Depth/95253-6.html) - Investigates the anatomy of a link, how links affect page ranking, and the properties that make an excellent inbound link. With Peter Kent by Lynda.com.
- [Spying with SEO Tools](https://www.lynda.com/Marketing-PPC-tutorials/Spying-SEO-Tools/371730-6.html) - Learn how to use SEO tools and techniques to research the competition online. Find out what keywords your competitors are optimizing for—and then outrank them on search engine results pages. With Anson Alexander by Lynda.com.
- [WordPress Plugins: SEO](https://www.lynda.com/WordPress-tutorials/WordPress-Plugins-SEO/140779-2.html) - Drive more visitors to your WordPress site by performing search engine optimization, or SEO, with the help of two powerful plugins. With Morten Rand-Hendriksen by Lynda.com.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
