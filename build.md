YouTube-Extended: 18.17.43  
YouTube: 18.23.35  
Music (arm64-v8a): 5.39.52  
Music (arm-v7a): 5.39.52  
Music-Extended (arm64-v8a): 6.06.52  
Music-Extended (arm-v7a): 6.06.52  
Twitter: 9.93.0-release.1  
Twitch: 14.6.1  
TikTok: 30.0.2  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  

YouTube
==
- feat(youtube/default-video-quality): rollback to previous commit
- feat(youtube/hide-general-ads): added some exceptions
- feat(youtube/hide-seekbar): updated patch description https://github.com/inotia00/ReVanced_Extended/issues/1013
- fix(youtube/protobuf-spoof): playing a clip will play the video from the start https://github.com/inotia00/ReVanced_Extended/issues/999
- fix(youtube/protobuf-spoof): subtitles appear at top when you watch related shorts https://github.com/inotia00/ReVanced_Extended/issues/1011
- fix(youtube/sponsorblock): not reflected in the patch information
- feat(youtube/translations): update translation
`Chinese Simplified`, `Greek`, `Indonesian`, `Italian`, `Japanese`, `Russian`, `Spanish`, `Vietnamese`


YouTube Music
==
- feat(music/hide-new-playlist-button): change patch name https://github.com/inotia00/ReVanced_Extended/issues/983
- feat(music/translations): update translation
`Chinese Simplified`


※ Compatible ReVanced Manager: v1.1.0
[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)
---

### [2.177.0](https://github.com/revanced/revanced-patches/compare/v2.176.1...v2.177.0) (2023-06-12)
### Bug Fixes
* **reddit/hide-ads:** search for correct reference class descriptor ([ad2a858](https://github.com/revanced/revanced-patches/commit/ad2a8585b2a5ecbc5eb92dd23b0ab124aa8a2541))
* **syncforreddit/change-oauth-client-id:** trim whitespace from OAuth string ([#2402](https://github.com/revanced/revanced-patches/issues/2402)) ([2afea71](https://github.com/revanced/revanced-patches/commit/2afea71557cfe4eb64d7c7ebf5a07dfd24a11824))
* **syncforreddit/change-oauth-client-id:** use downloads directory ([9b5af77](https://github.com/revanced/revanced-patches/commit/9b5af77a229a22466cfe8ed41a21d081beeae960))
### Features
* **syncforreddit/change-oauth-client-id:** support pro version ([d34288b](https://github.com/revanced/revanced-patches/commit/d34288b6e8c7f5bb944622a3c741fcc693868033))

---  
