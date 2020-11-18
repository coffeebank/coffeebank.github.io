---
layout: landing

user: Nightscape Sylvia
profile: https://github.com/coffeebank
avatar: https://avatars3.githubusercontent.com/u/23473065

bio: "Looking out into the starry sky, sipping a nice cup of coffee ☕"

badges:
  - bname: Web Designer
    burl: "#sites"
  - bname: Cat Enthusiast
    burl: /cats

sitelist:
  - sname: Wysc
    ssubline: Virtual Study Cafe
    surl: /wysc
    simage: /home/media/wysc02.jpg
    sdesc: "For students striving to be better, Wysc is the study Discord server that delivers a cohesive, global online studying experience, as the first Discord server to present an edu-social cafe experience to an audience of hundreds."
    sdescurl: https://wysc.us.to
    sbadges:
      - Jekyll
      - Bootstrap
      - Documentation
    ssection:
      - ssname: Wysc&#12539;Virtual Study Cafe
        ssurl: /wysc
        ssimage: /home/media/wyscsite_min.jpg
        ssdesc: A web app built to inform and impress. Uses deferred content loading techniques to load pages quickly and polyfills to extend browser support. Equipped with Open Graph tags for social media, Widgetbot for live chat support, and progressive web app support for iOS, Android, and Chrome. Hosted on GitHub Pages in Jekyll.
        ssbadges:
          - PWA
          - Bootstrap
          - Browser Support
          - Live chat widget
          
      - ssname: Wyscraft - Minecraft Server
        ssurl: /wyscraft
        ssimage: /home/media/wyscraft01.png
        ssdesc: Uses Jekyll to bring a simple Minecraft website template to life. Allows easy config.yml startup with easily extendable page redirects, content pages, and customization options that provide a unified home for all Minecraft server content outside of Discord.
        ssbadges:
          - Jekyll
          - Server Status API
          
      - ssname: Wysc Docs
        ssurl: /wysc/docs
        ssimage: /home/media/wyscsitedocs01_min.jpg
        ssdesc: A documentation system made for Wysc that leverages Jekyll to create an easy-to-update repository of data and features. Features an alert system powered by Fetch API, search by Lunr.js (coming soon), breadcrumbs for SEO, and Anchorjs for heading anchors on hover.
        ssbadges:
          - Jekyll
          - Lunr.js
          - SEO

      - ssname: Wysc Blog
        ssurl: /wysc/blog
        ssimage: /home/media/wyscsiteblog01_min.jpg
        ssdesc: A blog system made for Wysc that leverages Jekyll to recreate a live experience on a static website. Features a static json API that can be easily updated, which is connected to the Wysc Blog homepage by Fetch API to reflect status updates. Latest three blog posts are shown, with a "Load more posts" button. Comes with an RSS feed updated automatically by Jekyll.
        ssbadges:
          - Jekyll
          - Json API
          - Fetch API
          - RSS Feed

      - ssname: Work &middot; Studying &middot; Chilling
        ssurl: /wysc/joinwsc
        ssimage: /home/media/wyscjoinwsc_min.jpg
        ssdesc: (Deprecated) Provides a simple front-end webpage for WSC (Work &middot; Studying &middot; Chilling), geared towards funnelling users to the WSC Discord. Features parallax images, Discord widget, and elements fading in on scroll, organized in an informative fashion.
        ssbadges:
          - Weebly
          - Landing page

  - sname: Myaa
    ssubline: Designing a premium showcase with deep integrations
    surl: /myaa
    simage: "/home/media/bailey-zindel-NRQV-hBF10M-unsplash_c02.jpg"
    sdesc: "A custom-built personal showcase that explores APIs from services to create a best-in-class user experience, unifying services and displaying fresh content to represent Myaa."
    sdescurl: https://myaa.netlify.app
    sbadges:
      - Vue.js
      - Tailwind
      - PWA
    ssection:
      - ssname: Anime
        ssurl: /myaa/anime
        ssimage: /home/media/am02.jpg
        ssdesc: Integrates recently watched/read feeds in a mobile-adaptive format. Backend is a simple list in the Vuex store. Data is lazily fetched, live from AniList, as user navigates through each page. Careful attention to UX through placeholders and responsive interface as data loads.
        ssbadges:
          - Vue.js
          - MyAnimeList (Jikan API)
          - AniList API
          - User Experience

      - ssname: Music
        ssurl: /myaa/music
        ssimage: /home/media/am03.jpg
        ssdesc: UI design inspired by Spotify. Backend is a simple list of playlist IDs. Retrieves user playlist images, song data, and music samples directly from Spotify Web API. UX considerations include playlist song counts, autostop when playing new sample, and visual indicators for no-sample songs.
        ssbadges:
          - Vue.js
          - Spotify Web API
          - HTML5 Audio

      - ssname: Emotes
        ssurl: /myaa/emotes
        ssimage: /home/media/am04.jpg
        ssdesc: A frontend for a saved archive of liked Discord emotes. Easily click to copy image URLs with a satisfying app-like experience. Performance enhancements include swipe to switch tabs, lazy loaded images, and click-to-play for animated emotes.
        ssbadges:
          - Vuetify JS
          - Javascript
          - Sheepicon

  - sname: Personal Projects
    ssubline: Web Apps, Landing Pages, and more
    surl: /
    simage: /home/media/aaron-lau-EOnlL3L3IgQ-unsplash_min.jpg
    sdesc: "Trying out a handful of technologies to create progressive web apps, landing pages, services, and more. Drop by my Github and say hi!<br><br>Current portfolio site built using Jekyll and Tailwind. Modals powered by Micromodaljs, icons by Feather Icons, images from Jaro Bielik and Aaron Lau (no affiliation)."
    sdescurl: https://github.com/coffeebank
    sbadges:
      - Free/Open Source
      - Landing page
    ssection:
      - ssname: Sheepicon
        ssurl: /sheepicon
        ssimage: /home/media/sheepicon.jpg
        ssdesc: A quick, clean dashboard for saving and copying image links easily, including Discord emotes. Thanks to Markdown, links are easy to add, save, and publish. Responsively designed, caches for offline use, and includes a REST API for those making custom frontends!
        ssbadges:
          - Free/Open Source
          - Jekyll
          - Tailwind
          - Javascript

      - ssname: Moonrise MC
        ssurl: /moonrise
        ssimage: /home/media/crispmc.jpg
        ssdesc: A simple, lightweight, responsive landing page template for a Minecraft server. Server name and IP can be easily changed. IP background changes when server goes offline. Integrates Discord via Widgetbot, and Minecraft server status with Mcsrvstat.us.
        ssbadges:
          - Free/Open Source
          - Tailwind
          - Fetch API
          - Minecraft

      - ssname: Arland - Minecraft Server
        ssurl: /arland
        ssimage: /home/media/arlandpwa_min.jpg
        ssdesc: The primary landing page for all things Arland. Modernizes Arland's web properties by utilizing MaterializeCSS to implement a material design look and feel that is responsive across all screen sizes. Experiments with noscript fallbacks, <code>position:sticky</code>, z-index, and animated scrolling to page anchors.
        ssbadges:
          - PWA
          - MaterializeCSS
          - Material Design

      - ssname: Arland Blog
        ssurl: /arland/blog/
        ssimage: /home/media/arlandpwa02.jpg
        ssdesc: Recreating the Weebly blog experience in Jekyll. Disqus comments replaced with a Fetch API experience that pulls comments from GitHub. Social media share widgets are replaced with Clipboardjs, "See more" shows all posts quicker upon click, and status indicator pulls from an easy-to-update html file (shows on homepage for larger screens).
        ssbadges:
          - Jekyll
          - GitHub API
          - Weebly

      - ssname: Arland Mobile
        ssurl: /arland/arlandapp
        ssimage: /home/media/arlandapp_min.jpg
        ssdesc: (Deprecated) A mobile website for Arland, created using W3CSS, javascript tabs, back buttons, iframes, and animations.
        ssbadges:
          - W3CSS
          - Mobile

---
