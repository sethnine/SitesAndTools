# SitesAndTools
This is a collection of useful sites and tools that I regularly forget exist.

# Web

## HeroIcons
A set of free, MIT-licensed high-quality SVG icons for you to use in your web projects.
> https://heroicons.com/

## Tailwind
A utility-first CSS framework for rapidly building custom user interfaces.
> https://tailwindcss.com/

## Bootstrap
The most popular HTML, CSS, and JS library in the world.
> https://getbootstrap.com/

## VueJS Docs
The official documentation for Vue.js, a progressive JavaScript framework.
> https://vuejs.org/v2/guide/

## Nuxtjs Docs
The official documentation for Nuxt.js, a framework for creating Universal Vue.js Applications.
> https://nuxtjs.org/docs/2.x/get-started

## Nextjs Docs
The official documentation for Next.js, a React framework for production.
> https://nextjs.org/docs

## Reactjs Docs
The official documentation for React, a JavaScript library for building user interfaces.
> https://reactjs.org/docs/getting-started.html

## Shadcn
A css framework for react
> https://ui.shadcn.com/docs/

# Linux

## NixOS Package Search
The official package lookup for NixOS
> https://search.nixos.org/packages/

## NixOS NixPkgs Manual
The official NixPkgs Manual
> https://nixos.org/manual/nixpkgs/stable/

## NixOS Manual
The official referance guide to NixOS
> https://nix.dev/manual/nix/stable/

## Home Manger
Manage you home with nix!
> https://nix-community.github.io/home-manager/

## Ubuntu
Ubuntu means community.
> https://ubuntu.com/

## Debian
> https://www.debian.org/

## Herbsluftwm
A window manager that tiles? looks good
> https://herbstluftwm.org/

## Guix
A GNU os much like NixOS. Less packages, but totally free.
> https://guix.gnu.org/

# Crontab Guru
A website that describes your crontab
> https://crontab.guru

# Self Hosting

## Vault Warden
Mom: we have Bitwarden at home
Bitwarden at home:
> https://github.com/dani-garcia/vaultwarden

## CDM-Project
A Self hosted Git Service
> https://cdm-project.com/

# Literature
i.e git gud

## How to ask questions better online
Smarter questions
> https://www.psychocats.net/ubuntucat/getting-the-best-help-on-linux-forums/
> http://catb.org/~esr/faqs/smart-questions.html

## Perfect Media Server
A plan to build your own media server
> https://perfectmediaserver.com/

# MISC

## Authorised Pearson Vue Test Centre 
Quill Learning
> https://quill.com.au/pages/test-centre

## Sysinternals
Useful tools such as a TCP viewer.
> https://live.sysinternals.com/

## Wikiwand
Wikipedia with improvements
> https://www.wikiwand.com/

## GitHub Flavored Markdown Spec
The specification for formatting markdown documents such as this one.
> https://github.github.com/gfm/

## Cloudflare Dashboard
The Cloudflare dashboard
> https://dash.cloudflare.com/

## Acceptable ads
Adblock Plus designed rules for ads that are considered acceptable to most users. Guidelines.
> https://acceptableads.com/standard/
> https://adblockplus.org/acceptable-ads

## Now payments
Accept crypto payments in twich
> https://nowpayments.io/twitch

## Web Server for Chrome
An in browser http server, absolutely cursed
> https://chromewebstore.google.com/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?pli=1

## DreamBerd
The perfect programming language
> https://github.com/TodePond/DreamBerd

# Adnauseam
What if your computer clicked the ads for you?
> https://adnauseam.io/

## Apex Chip
An human implantable NFC / RFIC chip
> https://vivokey.com/apex/

## Nix Language Basics
> https://nixos.org/guides/nix-language.html#reading-nix-language

# Bigtech lacking

## That one time someone got a copyrwrite notice for downloading linux
Downloading Ubuntu via BitTorrent gets Comcast customer a DMCA warning 
> https://arstechnica.com/gadgets/2021/05/fake-dmca-takedown-notice-targeted-ubuntu-downloaders-yesterday/

## That time google advertised malware at the top of search results
> https://www.ic3.gov/Media/Y2022/PSA221221

# Games
## Factorio
### Automatic Train painter
Trains automatically colored based on cargo
> https://mods.factorio.com/mod/Automatic_Train_Painter
### Vibrant trains
These trains pratically glow!
> https://mods.factorio.com/mod/vibrant-trains
### Train Trails
Trains leave a trail in their wake the same color as them.
> https://mods.factorio.com/mod/train-trails
### Logistic Train Network
Goods are transfered between stations automatically
> https://mods.factorio.com/mod/LogisticTrainNetwork
### Spidertron Automation
Adds in construction spidertrons which make logistic network requests for what they need to build with.
> https://mods.factorio.com/mod/Constructron-Continued

# Bookmarklets

## Debian Man Pages
Search the Man Pages of debian packages
```
javascript: (() => {
    let query = prompt("ManPages Query:");
    let url = "https://manpages.debian.org/" + encodeURIComponent(query + ".html");
    if (query == null) {
        console.log("ManPages bookmarklet: query cancelled");
        return;
    }
    console.log("ManPages bookmarklet: going to " + url);
    window.open(url, "_blank", "location=yes,height=800,width=735,scrollbars=yes,status=no");
})();
```

## Arch Man Pages

```
javascript: (() => {
    let query = prompt("ManPages Query:");
    let url = "https://man.archlinux.org/man/" + encodeURIComponent(query + ".html");
    if (query == null) {
        console.log("ManPages bookmarklet: query cancelled");
        return;
    }
    console.log("ManPages bookmarklet: going to " + url);
    window.open(url, "_blank", "location=yes,height=800,width=735,scrollbars=yes,status=no");
})();

```

## ChatGPT
Ask ChatGPT a question
```
javascript: (() => {
    let query = prompt("Ask ChatGPT:");
    let url = "https://chatgpt.com/?q=" + encodeURIComponent(query);
    if (query == null) {
        console.log("ChatGPT bookmarklet: query cancelled");
        return;
    }
    console.log("ChatGPT bookmarklet: going to " + url);
    window.open(url, "_blank", "location=yes,height=800,width=735,scrollbars=yes,status=yes");
})();
```

## ip lookup
plaintext ip from http request, ipv4/6 subdomains
> https://www.icanhazip.com/

# Games

## Snake
The best snake clone
> https://patorjk.com/games/snake/
