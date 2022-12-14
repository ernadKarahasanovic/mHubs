# [Mozilla Hubs](https://hubs.mozilla.com/)

[![License: MPL 2.0](https://img.shields.io/badge/License-MPL%202.0-brightgreen.svg)](https://opensource.org/licenses/MPL-2.0) [![Build Status](https://travis-ci.org/mozilla/hubs.svg?branch=master)](https://travis-ci.org/mozilla/hubs) [![Discord](https://img.shields.io/discord/498741086295031808)](https://discord.gg/CzAbuGu)

The client-side code for [Mozilla Hubs](https://hubs.mozilla.com/), an online 3D collaboration platform that works for desktop, mobile, and VR platforms.

[Learn more about Hubs](https://hubs.mozilla.com/docs/welcome.html)

## Getting Started

If you would like to run Hubs on your own servers, check out [Hubs Cloud](https://hubs.mozilla.com/docs/hubs-cloud-intro.html).

If you would like to deploy a custom client to your existing Hubs Cloud instance please refer to [this guide](https://hubs.mozilla.com/docs/hubs-cloud-custom-clients.html).

If you would like to contribute to the main fork of the Hubs client please see the [contributor guide](./CONTRIBUTING.md).

If you just want to check out how Hubs works and make your own modifications continue on to our Quick Start Guide.

### Quick Start

[Install NodeJS](https://nodejs.org) if you haven't already. We use 16.16.0 on our build servers. If you work on multiple javascript projects it may be useful to use something like [NVM](https://github.com/nvm-sh/nvm) to manage multiple versions of node for you.

Run the following commands:

```bash
git clone https://github.com/mozilla/hubs.git
cd hubs
# nvm use v16.16.0 # if using NVM
npm ci
npm run dev
```
fJZn307smG




The backend dev server is configured with CORS to only accept connections from "hubs.local:8080", so you will need to access it from that host. To do this, you likely want to add "hubs.local" and "hubs-proxy.local" to the [local "hosts" file](https://phoenixnap.com/kb/how-to-edit-hosts-file-in-windows-mac-or-linux) on your computer:

```
127.0.0.1	hubs.local
127.0.0.1	hubs-proxy.local
```

Then visit https://hubs.local:8080 (note: HTTPS is required, you'll need to accept the warning for the self-signed SSL certificate)

> Note: When running the Hubs client locally, you will still connect to the development versions of our [Janus WebRTC](https://github.com/mozilla/janus-plugin-sfu) and [reticulum](https://github.com/mozilla/reticulum) servers. These servers do not allow being accessed outside of localhost. If you want to host your own Hubs servers, please check out [Hubs Cloud](https://hubs.mozilla.com/docs/hubs-cloud-intro.html).

## Documentation

The Hubs documentation can be found [here](https://hubs.mozilla.com/docs).

## Community

Join us on our [Discord Server](https://discord.gg/CzAbuGu) or [follow us on Twitter](https://twitter.com/MozillaHubs).

## Contributing

Read our [contributor guide](./CONTRIBUTING.md) to learn how you can submit bug reports, feature requests, and pull requests.

We're also looking for help with localization. The Hubs redesign has a lot of new text and we need help from people like you to translate it. Follow the [localization docs](./src/assets/locales/README.md) to get started.

Contributors are expected to abide by the project's [Code of Conduct](./CODE_OF_CONDUCT.md) and to be respectful of the project and people working on it.

## Additional Resources

* [Reticulum](https://github.com/mozilla/reticulum) - Phoenix-based backend for managing state and presence.
* [NAF Janus Adapter](https://github.com/mozilla/naf-janus-adapter) - A [Networked A-Frame](https://github.com/networked-aframe) adapter for the Janus SFU service.
* [Janus Gateway](https://github.com/meetecho/janus-gateway) - A WebRTC proxy used for centralizing network traffic in this client.
* [Janus SFU Plugin](https://github.com/mozilla/janus-plugin-sfu) - Plugins for Janus which enables it to act as a SFU.
* [Hubs-Ops](https://github.com/mozilla/hubs-ops) - Infrastructure as code + management tools for running necessary backend services on AWS.

## Privacy

Mozilla and Hubs believe that privacy is fundamental to a healthy internet. Read our [privacy policy](https://www.mozilla.org/en-US/privacy/hubs/) for more info.

## License

Hubs is licensed with the [Mozilla Public License 2.0](./LICENSE)


https://www.infiniteloop.co.jp/tech-blog/2022/02/mozilla-hubs-on-virtualbox/

https://www.youtube.com/watch?v=NiINMxfLXSw


https://travistidwell.com/jsencrypt/demo/

https://threejs-journey.com/lessons/37#

https://www.howtoforge.com/tutorial/debian-minimal-server/

https://github.com/albirrkarim/mozilla-hubs-installation-detailed

https://super-unix.com/superuser/linux-copying-from-one-file-to-another-using-nano-editor/
167 .235  
/*/*/*/*/*/*/*/*/
https://github.com/albirrkarim/mozilla-hubs-installation-detailed/commit/fc316a9287df022c7ad7de87c6a203161cf49131
/*/*/*/*/*/*/*/*/*

https://superuser.com/questions/1214159/how-to-change-debian-linux-domainname

.136   .40


https://stackoverflow.com/questions/66757403/send-data-variable-from-child-to-parent-using-vuejs


https://ue5study.com/unrealengine-mobile/


https://qiita.com/wirsind55/items/b409fb9b0ff4ceb6eb9d

https://zenn.dev/kou029w/articles/hubs-custom-reticulum


https://stackoverflow.com/questions/71754121/how-to-use-fullcalendar-with-nuxt3-getting-vite-ssr-import-1-is-not-defined


https://www.youtube.com/watch?v=dRuI5KsUh7Y

https://framesynthesis.jp/tech/hubs/

https://hackmd.io/@XR/openmetaverse
