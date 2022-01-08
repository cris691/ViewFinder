<p align=center><a href=https://dosyago.com target=_blank><img src=https://github.com/i5ik/ViewFinder/raw/boss/.github/26881_DOSY_PP-01.png width=61.8%></a></p>

# [Viewfinder](https://github.com/i5ik/Viewfinder) · [![PRs welcome](https://camo.githubusercontent.com/b0ad703a46e8b249ef2a969ab95b2cb361a2866ecb8fe18495a2229f5847102d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e2e737667)](https://github.com/i5ik/Viewfinder/pulls) [![npm](https://img.shields.io/npm/v/remoteview)](https://npmjs.com/package/remoteview) [![visits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fc9fe%2FViewFinder&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%28today%2Ftotal%29%20visits%20since%2027%2f10%2f2020&edge_flat=false)](https://hits.seeyoufarm.com) [![npm](https://img.shields.io/npm/dt/remoteview)](https://npmjs.com/package/remoteview) [![Docker Pulls](https://img.shields.io/docker/pulls/dosyago/browsergapce)](https://hub.docker.com/r/dosyago/browsergapce) 

What is Viewfinder? It's a HTML user-interface for a browser that runs on a remote server. This means you can embed a browser UI on your website and provide unrestricted access to web resources in a way that's both more sandboxed than, and less restricted than, traditional web `<iframe>` elements. In also enables the building of a number of interesting [applications](#applications).

## Pro or Regular? 

What's the difference between VF Pro and regular VF? The main differences are that VF Pro has more advanced features and more frequent updates than VF regular. Many Pro features eventually are sent down to regular, but some will likely remain exclusive to Pro. Pro is updated weekly, with major updates shipped every quarter, whereas regular VF follows a much slower and more haphazard release cycle. 

The final main differenece you might want to be aware of is that while VF regular is source-available (and is the sourcecode in this repository), VF Pro is currently closed-source proprietary software only available commercially, for either use in an Individual server, or for deployment in a Self-hosted package. 

More information on these [commercial options](#commercial-options) is below, and take a look at this table of feature comparison between Regular and Pro.

| Feature                                       | Regular            | Pro                |
|-----------------------------------------------|--------------------|--------------------|
| Browser features                              | :heavy_check_mark: | :heavy_check_mark: |
| Security features                             | :heavy_check_mark: | :heavy_check_mark: |
| Privacy features                              | :heavy_check_mark: | :heavy_check_mark: |
| Themeable browser UI                          | :heavy_check_mark: | :heavy_check_mark: |
| Docker image                                  | :heavy_check_mark: | :heavy_check_mark: |
| Cloud and platform agnostic                   | :heavy_check_mark: | :heavy_check_mark: |
| Multi-user security features                  |                    | :heavy_check_mark: |
| Auto scaling and resource control             |                    | :heavy_check_mark: |
| Advanced viewport streaming and lag reduction |                    | :heavy_check_mark: |
| Built-in cobrowsing and instant messaging     |                    | :heavy_check_mark: |
| Run sandboxed puppeteer scripts               |                    | :heavy_check_mark: |
| `<iframe>` embeddable                         |                    | :heavy_check_mark: |
| Kiosk mode                                    |                    | :heavy_check_mark: |
| Simple API                                    |                    | :heavy_check_mark: |


## Commercial Options

Viewfinder Pro is provided by the [Dosyago Corporation](https://github.com/dosyago) as a commercial offering in two flavors: individual, and self-hosted.

**Self-hosted**

Includes the provision of software, license and various tiers of service. Basic cost principle is based on time (not scale): time you want the license for, time of the latest update you want, and time it takes us to service your deployment. Targeted at SMBs up to Enterprise. 

- Various configurable packages available with either perpetual or yearly licensing, and included service and consulting. 
- Starts at USD6,700 a year for non-perpetual single year license plus minimal service. 
- Mid-tier options cost 10K - 16K yearly with a variety of options including perpetual or annual licenses.
- Invoiceable service and consulting also available.
- BYO cloud or data-center, or on-prem are all available.

Prices and buy links for Self-hosted tiers are *coming soon!* In the meantime, <a href="mailto:cris@dosycorp.com?subject=VF%20Pro%20Packages&body=Hi%20Cris" target=_blank>email me</a> to ask a question.

**Individual**

Includes provision of a geographically located server wherever you want (or as close to it as possible for us), installed software, credentials to access, and various tiers of service. Basic cost principle is based on performance (CPU cores, memory, network speed and bandwidth amount). 

See the current [prices and tiers for the Individual track.](https://personal.dosyago.com)

## Applications

Some possible applications to build with Viewfinder:

**Product space**
- Remote browser isolation for security, risk mitigation and privacy
- Zero download co-browsing for collaboration and social interaction
- Delivery layer for a zero download web scraping app that works on any device format
- Alternate browser extension platform with associated app store
- An online "internet cafe" with advanced security and privacy features
- An alternative to VPNs, DNS blocklists
- Email attachment threat mitigation via CDR and automatic opening of links and attachments in the remote browser
- An intuitive UI affordance to enable clients to stay in-app while performing 3rd-party processes that normally require them to leave your web site.
- A fully skinable and themeable client-customizable online hosted web browser alternative to downloadable browsers
- Replay web app interactions to record bugs by recording the even stream and the viewport
- Record visual How To guides illustrating key user stories

**Internal tooling space**
- Human-in-the-loop intervention tool to unblock stuck browser automation jobs, and diagnose "selector drift" and script-page mismatch issues
- An effective web proxy to easily integrate 3rd-party processes without APIs
- An effective, interactive console to inspect, observe and interact with browser automation tasks
- An automatable browser that more effectively evades bot detection mechanisms that pure headless Chrome
- A scriptable console, and interactive simulator for automation tasks and automation script creation with a great, familiar and intuitive feedback loop

**Tech and framework space**
- A `<WebView>` tag for the open web
- An `<iframe>` without cross-origin restrictions 
- A 'head' for headless browsers

## Progress & Roadmap 

It's kind of a long road but--hey--we've come so far already, we're gonna keep going 😉 (⭐ *features are only in Viewfinder Pro*)

**Browser Features**
- [x] Back and forward history buttons 
- [x] Multiple tabs
- [x] Favicons
- [x] Addressbar search
- [x] Incognito tabs
- [x] Persistent sessions
- [x] `<select>` inputs
- [x] Modal dialogs
- [x] Copy and paste
- [x] Native paste
- [x] Touch scroll and touch drag
- [x] File upload (including multiple files)
- [x] Basic & Digest Auth support
- [x] Clear all cookies and cached data during sessions
- [x] Sound
- [x] Interact with CAPTCHAs
- [x] Context-menu (for opening in new tab, copying link address, etc)
- [x] Responsive design for any device viewport
- [x] Desktop scroll-zoom
- [x] Mobile pinch-zoom
- [x] `mailto:`, `tel:`, `sktype:` and other [app and protocol links](quora.com/What-are-tel-SMS-mailto-and-geo-in-URLs/answer/Matthew-Cox-33)
- [x] Multiple select 
- [ ] Multi-touch on mobile
- [ ] Bookmarks
- [ ] Displayable history
- [ ] Webcam and microphone support

**Security Features**
- [x] RBI [browser isolation](https://en.wikipedia.org/wiki/Browser_isolation) security model
- [x] Fully clientless, embeds straight into a web page, zero download required for front-end
- [x] [Evades](https://github.com/paulirish/headless-cat-n-mouse) [headless](https://github.com/infosimples/detect-headless) [detection](https://github.com/azerpas/detect-headless) 
- [x] Customizable browser-fingerprinting cross-section
- [x] Works with proxies and Tor
- [x] DevTools (*currently only works on Chrome clients*) ⭐
- [x] Integrates with PDF/DOCX/XLSX secure document viewer ([CDR](https://en.wikipedia.org/wiki/Content_Disarm_%26_Reconstruction)) (built-in only in Pro ⭐)
- [x] [`cgroups`](https://man7.org/linux/man-pages/man7/cgroups.7.html) resource control sandboxing ⭐
- [x] 1 temporary user account per browser session ⭐
- [x] Clean-slate profile directory per browser session ⭐

**Application Features**
- [x] Built-in AdBlocker
- [x] Fully remote real-time co-browsing + built-in chat ⭐
- [x] Advanced adaptive streaming (WebRTC + WebSockets) and Shortest path lag reduction ⭐
- [x] Run sandboxed puppeteer scripts ⭐
- [x] Skinnable browser UI ⭐
- [x] Kiosk mode (*no UI controls*) ⭐
- [ ] Sync browser cookies & settings from other browser (or, for example, Google account)
- [ ] Chrome extensions API (or cloned functionality)

**Development and Deployment Features**
- [x] Fully Dockerized / Dockerizable + reproducible startup and install scripts
- [x] Cloud-agnostic, runs on any cloud platform 
- [x] Platform agnostic, and runs on Windows, Linux and Mac
- [x] Dependency control and minimal dependencies (only 14 external 1st level deps on back-end--mostly [express](https://expressjs.com/) related--and 0 on front-end)
- [x] Many customizable settings (including site blocklist)
- [x] Embeddable in an `<iframe>` ⭐
- [x] Vertically scalable (multiple browsers per server) ⭐
- [x] Small resource footprint ⭐
- [x] Bandwidth, CPU and memory limiting for resource abuse detection and prevention ⭐
- [x] Simple API ⭐
- [x] Fully white-labelable
- [ ] White-labeling API
- [ ] Fully scriptable with comprehensive API 

## Motivation

I originally created this in 2018 as a layer for a collaborative zero-download clientless web-scraping app I'm working on, but fell in love with this browser layer, and decided it was useful enough and a product category in its own right. 

## Contributing

Contributions welcome! But please sign the CLA first. Don't worry, if you open a pull request a bot will automatically let you know what you need to do! 😜😉❤️

## Licensing

*Coming soon* 

## Copyright

This project copyright Cris Stringfellow & The Dosyago Corporation 2022

## FAQ

**Can you rush legacy Flash applications?**

There's a customized version of Viewfind Pro with Flash support via two separate paths: Legacy Chrome (pre [Chrome 88+ - Jan 2021](https://www.chromium.org/flash-roadmap#TOC-Flash-Support-Removed-from-Chromium-Target:-Chrome-88---Jan-2021-)) with [xvfb], and using latest Chrome with [ruffle](https://github.com/ruffle-rs/ruffle). ***However***, there's no guaruntee that your particular application will work, because ruffle still has many missing features and bugs, and because streaming your app over the network in a virtual browser may introduce other issues for your application, or simply be not suitable in your case.

But in the ideal case, yes, it can be done, and you can embed your legacy Flash player app in a VF Pro iframe and put it on your site.

**Can I download files form the web using VF?**

By default VF does not permit downloading of files to the local device, and instead downloads them to the remote server. In VF Pro, the built-in secure document viewer then processes and displays them if they are of a supported format. However, both Pro and Regular tracks can be configured to provide a download link to get the file to the local device, although that is not recommended in security applications, at least not without proper scanning or CDR.

**Can VF integrate with our existing secure document viewer or download scanning?**

Not out of the box but VF Pro can be configured to pass requests for document viewing to a 3rd-party application and to serve downloaded files. In short, VF can be configured to send downloads to your secure document viewer or download scanner. In the case where VF is configured to allow downloads to the local device, it should not effect your normal download scanners and endpoint protection software. 

**What sort of multi-profile or "fake profile" privacy options are available to defeat fingerprinting and tracking?**

By default VF Pro runs with a clean slate every session, so there are no tracking cookies or data retained from any other session of VF. Even if persistent sessions are enabled, VF can still be configured to transmit various phoney profile information (such as installed plugins, geolocation, platform, device, browser version and so on) in order to attempt to defeat fingerprinting and tracking. However, even with the added layer of protection of an additional remote browser, a separate IP address, and forged browser identification, there's no guaruntee of 100% effectiveness. If someone logs in to an account linked to their other profiles or identities, it may still be possible to track them, even if they are using VF. Technology can only go so far, people must also take sensible precautions in their choices. 

**Can you white-label VF as the tech for our internal RBI product?**

Not us, but you can do it and we can help you. VF can most definitely be fully whitelabelled and customized with a variety of themes, splash pages, styles, design systems, brand look and assets.

**Can I use VF tech to make my own commercial RBI product and sell that?**

Yes of course. With the proper license this is most definitely a possible use case for VF, and we encourage you to do so.

**Where can I get more information on your services, available licenses or pricing?**

Eventually I intend to most of that information here, but for now you may [email me](mailto:cris@dosycorp.com?subject=VF%20Info&body=Hi%20Cris). The reason is I'm currently revising a lot of positioning, licensing and prices. If you let me know you prefer a voice call that's also available. 

## Other sections - coming soon

- Click to deploy on GCP, AWS, Heroku
- Planned: StackScript for Linode, Vultr Marketplace entry
- Some sort of community page: Matrix? Reddit? Usenet? Kidding ... probably ? 




