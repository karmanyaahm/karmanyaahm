This is my overly detailed portfolio. Items with a ⭐ are important.
Roughly reverse chronological

## [UnifiedPush](https://unifiedpush.org)

- ⭐ Make a [WebPush protocol decryption](https://github.com/UnifiedPush/dart-webpush-encryption) (RFC 8291, 8188) library in Dart for the Flutter ecosystem.

- ⭐ Wrote proof of concepts for push notification infrastructure on Linux based operating systems
  - Using [no server](https://github.com/NoProvider2Push/dbus) and the [NextPush server](https://github.com/karmanyaahm/nextpush_dbus). Written in Go.
  - Wrote [a library](https://github.com/karmanyaahm/go_nextcloud_authv2) to easily authenticate to NextCloud in Go Command Line apps.
  - Wrote [a library](https://github.com/UnifiedPush/go_dbus_connector) for Linux apps to use the UnifiedPush API.
  - Consult with KDE and [KUnifiedPush](https://invent.kde.org/libraries/kunifiedpush/), the leading push notification library for Mobile Linux.

- ⭐ Wrote, maintain, and host [common-proxies](https://github.com/UnifiedPush/common-proxies): a Go server to convert between UnifiedPush messages and Matrix, Gotify, Firebase Cloud Messaging, and Ubuntu Touch.

- Gotify (7.9k stars): Contribute support for public account registration
  - Worked with React for the UI and Go for the backend
  - [final PR](https://github.com/gotify/server/pull/394) / [my individual contributions](https://github.com/p1gp1g/server/pulls?q=is%3Apr+is%3Aclosed)
- ⭐ Wrote a [server API specification](https://github.com/UnifiedPush/specifications/pull/9)
- ⭐ [Official Documentation site](https://github.com/UnifiedPush/documentation)
  - Made the original site, and continue to maintain it and [host it](#server-stuff).
- Wrote the original Flutter connector library [commits](https://github.com/UnifiedPush/flutter-connector/commits?author=karmanyaahm)

## Vex Robotics

- Contributed [several features](https://github.com/OkapiLib/OkapiLib/pulls?q=is%3Apr+author%3Akarmanyaahm+) to OkapiLib, (arguably) the most important library in Vex Robotics programming.
- I made a cool CSS animation based printable field diagram. [website](https://karmanyaah.malhotra.cc/projects/spin-up-field-diagram/) [code](https://github.com/vex-76513/field-diagram-2022)
- Here's my 2021 [robot code](https://github.com/vex-76513/code)

## Messaging
- Wrote an (incomplete) [bridge](https://github.com/karmanyaahm/matrix-groupme-go) between the Matrix and Groupme chat platforms
  - [Contributed to and improved](https://github.com/densestvoid/groupme/pulls?q=is%3Apr+author%3Akarmanyaahm+) a Groupme library in Go
  - [Fixed a faye protocol connection library](https://github.com/autogrow/wray/pull/2)
- ⭐ Wrote a reliable bridge between [GroupMe and Discord](https://github.com/karmanyaahm/groupme_discord_bridge_v3) in Go
  - This has been working uninterrupted since 2020 (as of mid 2022)

- [Contributed authentication](https://gitlab.com/cactus-comments/cactus-appservice/-/merge_requests/3) to the Cactus Comments server - A matrix based website comments section
  - [My blog post about that](https://karmanyaah.malhotra.cc/tech/2021/06/website-things/)

## Server stuff

- Report and help debug [an issue](https://github.com/ipfs/kubo/issues/8293) in Go-IPFS 
- IPFS Based website host
  - [blog post](https://karmanyaah.malhotra.cc/tech/2021/07/ipfsifying-documentation/#host-setup)
  - [Ansible code on GitLab](https://gitlab.com/karmanyaahm/site-host-deployment)
- My personal server [infrastructure in Ansible](https://gitlab.com/karmanyaahm/infrastructure/-/tree/master/roles)

## Random
- Currently working on a cheap and fast Keystroke Injection device. Not much to see yet but here's [v2 of the code](https://github.com/karmanyaahm/rubber_ducky/tree/main/v2win).
- Wrote a tool in Python (and rewrote in Go) to sort and organize a bunch of files (Science Olympiad Tests) based on their filename, and then upload them to Google Drive. [code](https://github.com/karmanyaahm/test_organization)
- Wrote a Web UI to see the list of the above. [code](https://github.com/karmanyaahm/scioly-test-frontend) [website](https://scioly.karmanyaah.malhotra.cc/)

- Contribute a minor HTML rendering fix to [Celehner's Gemini feed-expanding proxy](https://portal.mozz.us/gemini/celehner.com/proxy/)
- ⭐ Contribute [several features and fixes](https://github.com/snoe/deedum/pulls?q=is%3Apr+author%3Akarmanyaahm+) to the Gemini protocol browser deedum written in Flutter for Android and iOS
- Submit [a critical bugfix](https://lists.sr.ht/~sircmpwn/gmni-devel/patches/23416) to the Gemini server gmnisrv written in C

- A (partially functional) bot to send updates [from Google Classroom to Discord](https://github.com/karmanyaahm/google_classroom_discord_feed)
  - Learned a lot of new tech like OAuth (i.e. Sign in with Google) and Google Cloud Pub Sub messaging
