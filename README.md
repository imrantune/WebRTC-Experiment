# WebRTC Demos, Experiments, Libraries, Examples

* It is a [repository](https://github.com/muaz-khan/WebRTC-Experiment) of uniquely experimented WebRTC demos; written by [Muaz Khan](http://www.muazkhan.com/)!
* No special requirement! Just WebRTC compatible web-browser (e.g. chrome/firefox/opera on desktop/android)
* These demos/experiments are mostly client-side; i.e. no server installation needed!
* You can use all these demos in PHP/Python/Ruby/ASP.NET/etc. since they are only relying on JavaScript and 3rd party services!

# How to use?

**Each demo has a [unique directory](https://github.com/muaz-khan/WebRTC-Experiment). Simply download that directory, upload in your webserver and use it; and it'll work!**

> You don't need to modify any single line to use it. No single installation or modification is needed :)

# DetectRTC | Is WebRTC Supported In Your Browser?

A tiny JavaScript library that can be used to detect WebRTC features e.g. system having speakers, microphone or webcam, screen capturing is supported, number of audio/video devices etc.

Live Demo: https://www.webrtc-experiment.com/DetectRTC/

[![npm](https://img.shields.io/npm/v/detectrtc.svg)](https://npmjs.org/package/detectrtc) [![downloads](https://img.shields.io/npm/dm/detectrtc.svg)](https://npmjs.org/package/detectrtc)  [![Build Status: Linux](https://travis-ci.org/muaz-khan/DetectRTC.png?branch=master)](https://travis-ci.org/muaz-khan/DetectRTC)

Github (open sourced): https://github.com/muaz-khan/DetectRTC

# RecordRTC | WebRTC Audio+Video+Screen Recording

WebRTC JavaScript library for audio/video as well as screen activity recording. It supports Chrome, Firefox, Opera, Android, and Microsoft Edge. Platforms: Linux, Mac and Windows.

Live Demo: https://www.webrtc-experiment.com/RecordRTC/

[![npm](https://img.shields.io/npm/v/recordrtc.svg)](https://npmjs.org/package/recordrtc) [![downloads](https://img.shields.io/npm/dm/recordrtc.svg)](https://npmjs.org/package/recordrtc) [![Build Status: Linux](https://travis-ci.org/muaz-khan/RecordRTC.png?branch=master)](https://travis-ci.org/muaz-khan/RecordRTC)

Github (open sourced): https://github.com/muaz-khan/RecordRTC

# RTCMultiConnection

WebRTC JavaScript library for peer-to-peer applications (screen sharing, audio/video conferencing, file sharing, media streaming etc.)

[![npm](https://img.shields.io/npm/v/rtcmulticonnection.svg)](https://npmjs.org/package/rtcmulticonnection) [![downloads](https://img.shields.io/npm/dm/rtcmulticonnection.svg)](https://npmjs.org/package/rtcmulticonnection) [![Build Status: Linux](https://travis-ci.org/muaz-khan/RTCMultiConnection.png?branch=master)](https://travis-ci.org/muaz-khan/RTCMultiConnection)

Github: https://github.com/muaz-khan/RTCMultiConnection

Socket.io signaling server: https://github.com/muaz-khan/RTCMultiConnection-Server

# WebRTC Chrome Extensions

WebRTC chrome extensions for screen sharing, screen recording, file sharing, youtube+audio sharing, etc.

| Description        | Download           | Install |
| ------------- |-------------|-------------|
| Record full screen, apps' screen, youtube audio, and more. | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/screen-recording) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/recordrtc/ndcljioonkecdnaaihodjgiliohngojp) |
| Share full screen, apps' screen, youtube audio, and more. | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/desktopCapture-p2p) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/webrtc-desktop-sharing/nkemblooioekjnpfekmjhpgkackcajhg)  |
| Access/capture screen from any HTTPs domain. | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/desktopCapture) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/screen-capturing/ajhifddimkapgcifgcodmmfdlknahffk) |
| Share selected tab (peer-to-peer). | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/tabCapture) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/tab-capturing-sharing/pcnepejfgcmidedoimegcafiabjnodhk) |
| Share files peer-to-peer. | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/file-sharing) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/tab-capturing-sharing/pcnepejfgcmidedoimegcafiabjnodhk) |
| Detect WebRTC Features | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/DetectRTC) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/detectrtc/infnkpmpcmmofkmndpheeplkcghgdjbf) |
| getUserMedia on HTTP | [Source Code](https://github.com/muaz-khan/Chrome-Extensions/tree/master/getUserMedia-on-http) | [Install from Google Web Store](https://chrome.google.com/webstore/detail/getusermedia/nbnpcmljmiinldficickhdoaiblgkggc) |

Github (open sourced): https://github.com/muaz-khan/Chrome-Extensions

# MultiStreamsMixer

Pass multiple streams (e.g. screen+camera or multiple-cameras) and get single stream.

Live Demo: https://www.webrtc-experiment.com/MultiStreamsMixer/

Github: https://github.com/muaz-khan/MultiStreamsMixer

# MediaStreamRecorder

Cross browser audio/video/screen recording. It supports Chrome, Firefox, Opera and Microsoft Edge. It even works on Android browsers. It follows latest MediaRecorder API standards and provides similar APIs.

Live Demos: https://www.webrtc-experiment.com/msr/

[![npm](https://img.shields.io/npm/v/msr.svg)](https://npmjs.org/package/msr) [![downloads](https://img.shields.io/npm/dm/msr.svg)](https://npmjs.org/package/msr) [![Build Status: Linux](https://travis-ci.org/streamproc/MediaStreamRecorder.png?branch=master)](https://travis-ci.org/streamproc/MediaStreamRecorder)

Github (open-sourced): https://github.com/streamproc/MediaStreamRecorder

# iOS and Android open-sourced apps

Source codes and demos are available here:

* https://github.com/muaz-khan/cordova-mobile-apps
* [See How to Write Android Apps](https://www.rtcmulticonnection.org/docs/Write-Android-Apps/)
* [See How to Write iOS Apps](https://www.rtcmulticonnection.org/docs/Write-iOS-Apps/)

# WebRTC Scalable Broadcasting

This module simply initializes socket.io and configures it in a way that single broadcast can be relayed over unlimited users without any bandwidth/CPU usage issues. Everything happens peer-to-peer!

Live Demo: https://rtcmulticonnection.herokuapp.com/demos/Scalable-Broadcast.html

[![npm](https://img.shields.io/npm/v/webrtc-scalable-broadcast.svg)](https://npmjs.org/package/webrtc-scalable-broadcast) [![downloads](https://img.shields.io/npm/dm/webrtc-scalable-broadcast.svg)](https://npmjs.org/package/webrtc-scalable-broadcast)

Github (open sourced): https://github.com/muaz-khan/WebRTC-Scalable-Broadcast


# WebRTC Firefox Addons

Firefox extension API are used to enable screen capturing flag for specific domains, etc.

Install from Firefox addons store: https://addons.mozilla.org/en-US/firefox/addon/enable-screen-capturing/

Github (open-sourced): https://github.com/muaz-khan/Firefox-Extensions

# WebRTC Dashboard | Canvas2D Drawing Tool

Collaborative, extendable, JavaScript Canvas2D drawing tool, supports dozens of builtin tools, as well as generates JavaScript code for 2D animations.

Live Demo: https://www.webrtc-experiment.com/Canvas-Designer/

Github (open-sourced): https://github.com/muaz-khan/Canvas-Designer

[![npm](https://img.shields.io/npm/v/canvas-designer.svg)](https://npmjs.org/package/canvas-designer) [![downloads](https://img.shields.io/npm/dm/canvas-designer.svg)](https://npmjs.org/package/canvas-designer) [![Build Status: Linux](https://travis-ci.org/muaz-khan/Canvas-Designer.png?branch=master)](https://travis-ci.org/muaz-khan/Canvas-Designer)

You video presentation: https://www.youtube.com/watch?v=pvAj5l_v3cM

# WebRTC Voice & Text Translator

Translator.js is a JavaScript library built top on Google Speech-Recognition & Translation API to transcript and translate voice and text. It supports many locales and brings globalization in WebRTC!

Live Demo: https://www.webrtc-experiment.com/Translator/

Github (open-sourced): https://github.com/muaz-khan/Translator

# getStats | Get WebRTC Peer Connection Stats

A tiny JavaScript library using WebRTC getStats API to return peer connection stats i.e. bandwidth usage, packets lost, local/remote ip addresses and ports, type of connection etc.

Live Demo: https://www.webrtc-experiment.com/getStats/

[![npm](https://img.shields.io/npm/v/getstats.svg)](https://npmjs.org/package/getstats) [![downloads](https://img.shields.io/npm/dm/getstats.svg)](https://npmjs.org/package/getstats)

Github (open-sourced): https://github.com/muaz-khan/getStats

# FileBufferReader | File Sharing

FileBufferReader is a JavaScript library reads file and returns chunkified array-buffers. The resulting buffers can be shared using WebRTC data channels or socket.io. 

Live Demo: https://www.webrtc-experiment.com/FileBufferReader/

Github (open-sourced): https://github.com/muaz-khan/FileBufferReader

[![npm](https://img.shields.io/npm/v/fbr.svg)](https://npmjs.org/package/fbr) [![downloads](https://img.shields.io/npm/dm/fbr.svg)](https://npmjs.org/package/fbr) [![Build Status: Linux](https://travis-ci.org/muaz-khan/FileBufferReader.png?branch=master)](https://travis-ci.org/muaz-khan/FileBufferReader)

Youtube video presentation: https://www.youtube.com/watch?v=gv8xpdGdS4o

# getScreenId | Capture screen from any domain

getScreenId | Capture Screen on Any Domain! This script is a hack used to support single chrome extension usage on any HTTPs domain.

[![npm](https://img.shields.io/npm/v/webrtc-screen-capturing.svg)](https://npmjs.org/package/webrtc-screen-capturing) [![downloads](https://img.shields.io/npm/dm/webrtc-screen-capturing.svg)](https://npmjs.org/package/webrtc-screen-capturing)

Live Demo: https://www.webrtc-experiment.com/getScreenId/

Youtube video presentation: https://www.youtube.com/watch?v=UHrsfe9RYAQ

Install this chrome extension (required): https://chrome.google.com/webstore/detail/screen-capturing/ajhifddimkapgcifgcodmmfdlknahffk

Github (open-sourced): https://github.com/muaz-khan/getScreenId

# WebRTC Video Conferencing Demos

* Simple Demo: https://rtcmulticonnection.herokuapp.com/demos/Video-Conferencing.html
* AppRTC like Demo: https://www.webrtc-experiment.com/RTCMultiConnection/AppRTC-Look.html
* Advance (skype-like) Demo: https://www.webrtc-experiment.com/RTCMultiConnection/MultiRTC/
* Old (simple) Demo: https://www.webrtc-experiment.com/video-conferencing/

# WebRTC File Sharing

* Advance file sharing demo: https://rtcmulticonnection.herokuapp.com/demos/file-sharing.html
* File sharing using FileBufferReader: https://www.webrtc-experiment.com/FileBufferReader/
* Old file sharing demo: https://www.webrtc-experiment.com/file-hangout/
* Old file sharing plus text chat demo: https://www.webrtc-experiment.com/RTCMultiConnection/group-file-sharing-plus-text-chat.html

# WebRTC Screen Sharing

* Recommended Google Chrome Extension for Screen Sharing: https://chrome.google.com/webstore/detail/webrtc-desktop-sharing/nkemblooioekjnpfekmjhpgkackcajhg
* Old Screen Sharing Demo: https://www.webrtc-experiment.com/Pluginfree-Screen-Sharing/
* Screen Sharing using `screen.js`: https://www.webrtc-experiment.com/screen-sharing/
* Latest Screen Sharing Demo: https://www.webrtc-experiment.com/RTCMultiConnection/screen-sharing.html
* Scalable Screen Sharing Demo: https://rtcmulticonnection.herokuapp.com/demos/Scalable-Screen-Broadcast.html

# WebRTC Part of Screen Sharing

* Latest part-of-screen sharing Demo: https://rtcmulticonnection.herokuapp.com/demos/share-part-of-screen.html
* Old part-of-screen sharing Demo: https://www.webrtc-experiment.com/RTCMultiConnection/RTCMultiConnection.sharePartOfScreen.html
* Cropped screen sharing Demo: https://www.webrtc-experiment.com/RTCMultiConnection/cropped-screen-sharing.html
* Simplest part-of-screen sharing Demo: https://www.webrtc-experiment.com/part-of-screen-sharing/firebase/
* Part-of-screen sharing Demo using `DataChannel.js`: https://www.webrtc-experiment.com/part-of-screen-sharing/webrtc-data-channel/
* Share only embedded iframe: https://www.webrtc-experiment.com/part-of-screen-sharing/iframe/
* Text chat screenshot sharing Demo: https://www.webrtc-experiment.com/part-of-screen-sharing/realtime-chat/No-WebRTC-Chat.html
* Record part-of-screen: https://www.webrtc-experiment.com/RecordRTC/Canvas-Recording/webpage-recording.html

# RecordRTC Demos

| DemoTitle        | TestLive           | ViewSource |
| ------------- |-------------|-------------|
| 16khz-audio-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/16khz-audio-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/16khz-audio-recording.html) |
| Record-Mp3-or-Wav.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/Record-Mp3-or-Wav.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/Record-Mp3-or-Wav.html) |
| RecordRTCPromisesHandler.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/RecordRTCPromisesHandler.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/RecordRTCPromisesHandler.html) |
| audio-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/audio-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/audio-recording.html) |
| auto-stop-on-silence.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/auto-stop-on-silence.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/auto-stop-on-silence.html) |
| bitsPerSecond.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/bitsPerSecond.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/bitsPerSecond.html) |
| calculate-recording-duration.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/calculate-recording-duration.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/calculate-recording-duration.html) |
| destroy.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/destroy.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/destroy.html) |
| edge-audio-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/edge-audio-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/edge-audio-recording.html) |
| gif-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/gif-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/gif-recording.html) |
| multi-audios-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/multi-audios-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/multi-audios-recording.html) |
| multi-cameras-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/multi-cameras-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/multi-cameras-recording.html) |
| onStateChanged.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/onStateChanged.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/onStateChanged.html) |
| onTimeStamp.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/onTimeStamp.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/onTimeStamp.html) |
| ondataavailable-StereoAudioRecorder.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/ondataavailable-StereoAudioRecorder.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/ondataavailable-StereoAudioRecorder.html) |
| ondataavailable.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/ondataavailable.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/ondataavailable.html) |
| pass-getUserMedia-constraints.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/pass-getUserMedia-constraints.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/pass-getUserMedia-constraints.html) |
| php-upload-jquery.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/php-upload-jquery.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/php-upload-jquery.html) |
| php-upload-simple-javascript.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/php-upload-simple-javascript.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/php-upload-simple-javascript.html) |
| preview-blob-size-during-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/preview-blob-size-during-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/preview-blob-size-during-recording.html) |
| raw-pcm.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/raw-pcm.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/raw-pcm.html) |
| record-cropped-screen.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/record-cropped-screen.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/record-cropped-screen.html) |
| recording-html-element.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/recording-html-element.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/recording-html-element.html) |
| reuse-same-instance.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/reuse-same-instance.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/reuse-same-instance.html) |
| setRecordingDuration.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/setRecordingDuration.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/setRecordingDuration.html) |
| show-animated-bar-on-video.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/show-animated-bar-on-video.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/show-animated-bar-on-video.html) |
| show-logo-on-recorded-video.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/show-logo-on-recorded-video.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/show-logo-on-recorded-video.html) |
| video-mirror-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/video-mirror-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/video-mirror-recording.html) |
| video-plus-screen-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/video-plus-screen-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/video-plus-screen-recording.html) |
| video-recording.html | [Demo](https://www.webrtc-experiment.com/RecordRTC/simple-demos/video-recording.html) | [Source](https://github.com/muaz-khan/RecordRTC/blob/master/simple-demos/video-recording.html) |

**Other RecordRTC demos:**

1. [RecordRTC to Node.js](https://github.com/muaz-khan/RecordRTC/tree/master/RecordRTC-to-Nodejs)
2. [RecordRTC to PHP](https://github.com/muaz-khan/RecordRTC/tree/master/RecordRTC-to-PHP)
3. [RecordRTC to ASP.NET MVC](https://github.com/muaz-khan/RecordRTC/tree/master/RecordRTC-to-ASPNETMVC)
4. [RecordRTC & HTML-2-Canvas i.e. Canvas/HTML Recording!](https://github.com/muaz-khan/RecordRTC/tree/master/Canvas-Recording)
5. [MRecordRTC i.e. Multi-RecordRTC!](https://github.com/muaz-khan/RecordRTC/tree/master/MRecordRTC)
6. [RecordRTC on Ruby!](https://github.com/cbetta/record-rtc-experiment)
7. [RecordRTC over Socket.io](https://github.com/muaz-khan/RecordRTC/tree/master/RecordRTC-over-Socketio)
8. [ffmpeg-asm.js and RecordRTC! Audio/Video Merging & Transcoding!](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/ffmpeg)
9. [RecordRTC / PHP / FFmpeg](https://github.com/muaz-khan/RecordRTC/tree/master/PHP-and-FFmpeg)
10. [Record Audio and upload to Nodejs server](https://www.npmjs.org/package/record-audio)
11. [ConcatenateBlobs.js](https://github.com/muaz-khan/ConcatenateBlobs) - Concatenate multiple recordings in single Blob!
12. [Remote audio-stream recording](https://www.webrtc-experiment.com/demos/remote-stream-recording.html) or [a real p2p demo](https://www.webrtc-experiment.com/RTCMultiConnection/RecordRTC-and-RTCMultiConnection.html)
13. [Record entire DIV including video, image, textarea, input, drag/move/resize, everything](https://www.webrtc-experiment.com/RecordRTC/Canvas-Recording/)
14. [Record canvas 2D drawings, lines, shapes, texts, images, drag/resize/enlarge/move via a huge drawing tool!](https://www.webrtc-experiment.com/RecordRTC/Canvas-Recording/record-canvas-drawings.html)
15. [Record Canvas2D Animation](https://www.webrtc-experiment.com/RecordRTC/Canvas-Recording/Canvas-Animation-Recording.html)
16. [WebGL animation recording](https://www.webrtc-experiment.com/RecordRTC/webgl/)
17. [Plotly - WebGL animation recording](https://www.webrtc-experiment.com/RecordRTC/plotly.html)

# RTCMultiConnection Demos

| DemoTitle        | TestLive           | ViewSource |
| ------------- |-------------|-------------|
| Audio+Video+File+TextChat | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Audio+Video+TextChat+FileSharing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Audio+Video+TextChat+FileSharing.html) |
| Pre-recorded media streaming (webm/mp3 live streaming) | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Pre-recorded-Media-Streaming.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Pre-recorded-Media-Streaming.html) |
| FileSharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/file-sharing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/file-sharing.html) |
| Scalable Audio/Video Broadcast | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Scalable-Broadcast.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Scalable-Broadcast.html) |
| Scalable Screen Broadcast | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Scalable-Screen-Broadcast.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Scalable-Screen-Broadcast.html) |
| Scalable Video Broadcast | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Video-Scalable-Broadcast.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Video-Scalable-Broadcast.html) |
| Scalable File Sharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Files-Scalable-Broadcast.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Files-Scalable-Broadcast.html) |
| Video Conferencing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Video-Conferencing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Video-Conferencing.html) |
| SSEConnection (Server Sent Events) | [Demo](https://rtcmulticonnection.herokuapp.com/demos/SSEConnection.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/SSEConnection.html) |
| Audio+Video+Screen Sharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Audio-Video-Screen.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Audio-Video-Screen.html) |
| One-to-One Video Chat | [Demo](https://rtcmulticonnection.herokuapp.com/demos/One-to-One.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/One-to-One.html) |
| Audio Conferencing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Audio-Conferencing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Audio-Conferencing.html) |
| Video Broadcasting | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Video-Broadcasting.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/blob/master/demos/video-broadcasting.html) |
| TextChat+FileSharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/TextChat+FileSharing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/TextChat+FileSharing.html) |
| addStream in a Chat room | [Demo](https://rtcmulticonnection.herokuapp.com/demos/addStream-in-Chat-room.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/addStream-in-Chat-room.html) |
| Part-of-Screen Sharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/share-part-of-screen.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/share-part-of-screen.html) |
| Share Audio+Screen | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Audio+ScreenSharing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Audio+ScreenSharing.html) |
| Screen Sharing | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Screen-Sharing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/screen-sharing.html) |
| Disconnect/Rejoin rooms | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Disconnect+Rejoin.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Disconnect+Rejoin.html) |
| Password Protected Rooms | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Password-Protected-Rooms.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Password-Protected-Rooms.html) |
| replaceTrack in Firefox | [Demo](https://rtcmulticonnection.herokuapp.com/demos/replaceTrack.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/replaceTrack.html) |
| applyConstraints in Firefox | [Demo](https://rtcmulticonnection.herokuapp.com/demos/applyConstraints.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/applyConstraints.html) |
| Firebase-Demo | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Firebase-Demo.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Firebase-Demo.html) |
| PubNub Demo | [Demo](https://rtcmulticonnection.herokuapp.com/demos/PubNub-Demo.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/PubNub-Demo.html) |
| Socket.io Custom-Messaging | [Demo](https://rtcmulticonnection.herokuapp.com/demos/custom-socket-event.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/custom-socket-event.html) |
| Check Rooms Presence | [Demo](https://rtcmulticonnection.herokuapp.com/demos/checkPresence.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/checkPresence.html) |
| Change Cameras/Microphone | [Demo](https://rtcmulticonnection.herokuapp.com/demos/switch-cameras.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/switch-cameras.html) |
| MultiRTC: Skype-like app | [Demo](https://rtcmulticonnection.herokuapp.com/demos/MultiRTC/) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/MultiRTC/) |
| Change Video Resolutions in your Live Sessions | [Demo](https://rtcmulticonnection.herokuapp.com/demos/change-resolutions.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/change-resolutions.html) |
| Admin/Guest demo | [Demo](https://rtcmulticonnection.herokuapp.com/demos/admin-guest.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/admin-guest.html) |
| Check if StreamHasData | [Demo](https://rtcmulticonnection.herokuapp.com/demos/StreamHasData.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/StreamHasData.html) |
| Capture & Share Screen from any domain! | [Demo](https://rtcmulticonnection.herokuapp.com/demos/Cross-Domain-Screen-Capturing.html) | [Source](https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/Cross-Domain-Screen-Capturing.html) |
| SignalR demo for RTCMultiConnection | -- | [Source](https://github.com/muaz-khan/RTCMultiConnection-SignalR) |

**Older demos (v2.2.2 or earlier):**

* https://github.com/muaz-khan/RTCMultiConnection/tree/master/v2.2.2

# MediaStreamRecorder Demos

| Experiment Name        | Demo           | Source Code |
| ------------- |-------------|-------------|
| **Audio Recording** | [Demo](https://www.webrtc-experiment.com/msr/audio-recorder.html) | [Source](https://github.com/streamproc/MediaStreamRecorder/tree/master/demos/audio-recorder.html) |
| **Video Recording** | [Demo](https://www.webrtc-experiment.com/msr/video-recorder.html) | [Source](https://github.com/streamproc/MediaStreamRecorder/tree/master/demos/video-recorder.html) |
| **Gif Recording** | [Demo](https://www.webrtc-experiment.com/msr/gif-recorder.html) | [Source](https://github.com/streamproc/MediaStreamRecorder/tree/master/demos/gif-recorder.html) |
| **MultiStreamRecorder Demo** | [Demo](https://www.webrtc-experiment.com/msr/MultiStreamRecorder.html) | [Source](https://github.com/streamproc/MediaStreamRecorder/tree/master/demos/MultiStreamRecorder.html) |

# Other WebRTC Libraries

* [navigator.customGetUserMediaBar.js](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/navigator.customGetUserMediaBar) / [Demo](https://www.webrtc-experiment.com/navigator.customGetUserMediaBar/)
* [File.js](https://www.webrtc-experiment.com/docs/Share-Files-using-Filejs.html) / [Demo](https://www.webrtc-experiment.com/WebRTC-File-Sharing/)
* [Meeting.js](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/meeting) / [Demo](https://www.webrtc-experiment.com/meeting/)
* [RTCall.js](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/RTCall) / [Demo](https://www.webrtc-experiment.com/RTCall/)
* [SdpSerializer.js](https://github.com/muaz-khan/SdpSerializer) / [Demo](https://www.webrtc-experiment.com/SdpSerializer/demo.html)
* [ConcatenateBlobs.js](https://github.com/muaz-khan/ConcatenateBlobs) / [Demos](https://www.webrtc-experiment.com/ConcatenateBlobs/)
* [getMediaElement.js](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/getMediaElement) / [Demo](https://www.webrtc-experiment.com/getMediaElement/)

# WebRTC Reliable Signaling Implementation

A reliable socketlio/node.js based signaling implementation for DataChannel.js, RTCMultiConnection.js and WebRTC Experiments.

[![npm](https://img.shields.io/npm/v/reliable-signaler.svg)](https://npmjs.org/package/reliable-signaler) [![downloads](https://img.shields.io/npm/dm/reliable-signaler.svg)](https://npmjs.org/package/reliable-signaler)

Github (open-sourced): https://github.com/muaz-khan/Reliable-Signaler

* `rtcmulticonnection-client`: [![npm](https://img.shields.io/npm/v/rtcmulticonnection-client.svg)](https://npmjs.org/package/rtcmulticonnection-client) [![downloads](https://img.shields.io/npm/dm/rtcmulticonnection-client.svg)](https://npmjs.org/package/rtcmulticonnection-client)
* `datachannel-client`: [![npm](https://img.shields.io/npm/v/datachannel-client.svg)](https://npmjs.org/package/datachannel-client) [![downloads](https://img.shields.io/npm/dm/datachannel-client.svg)](https://npmjs.org/package/datachannel-client)
* `videoconferencing-client`: [![npm](https://img.shields.io/npm/v/videoconferencing-client.svg)](https://npmjs.org/package/videoconferencing-client) [![downloads](https://img.shields.io/npm/dm/videoconferencing-client.svg)](https://npmjs.org/package/videoconferencing-client)

# Ffmpeg.js demos, both for browsers and node.js

Github (open-sourced): https://github.com/muaz-khan/Ffmpeg.js

| Demo Name        | Demo           | Code |
| ------------- |-------------|-------------|
| Transcoding WAV into AAC | [Demo](https://www.webrtc-experiment.com/ffmpeg/wav-to-aac.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/wav-to-aac.html) |
| Transcoding WAV into Ogg | [Demo](https://www.webrtc-experiment.com/ffmpeg/wav-to-ogg.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/wav-to-ogg.html) |
| Transcoding WebM into mp4 | [Demo](https://www.webrtc-experiment.com/ffmpeg/webm-to-mp4.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/webm-to-mp4.html) |
| Transcoding WebM into mp4; then merging WAV+mp4 into single mp4 | [Demo](https://www.webrtc-experiment.com/ffmpeg/merging-wav-and-webm-into-mp4.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/merging-wav-and-webm-into-mp4.html) |
| Recording Audio+Canvas and merging in single mp4 | [Demo](https://www.webrtc-experiment.com/ffmpeg/audio-plus-canvas-recording.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/audio-plus-canvas-recording.html) |
| Recording Audio+Screen and merging in single mp4 | [Demo](https://www.webrtc-experiment.com/ffmpeg/audio-plus-screen-recording.html)  | [Source](https://github.com/muaz-khan/Ffmpeg.js/blob/master/audio-plus-screen-recording.html) |

# DataChannel.js

DataChannel.js is a JavaScript library useful to write many-to-many i.e. group file/data sharing or text chat applications. Its syntax is easier to use and understand. It highly simplifies complex tasks like any or all user rejection/ejection; direct messages delivery; and more.

[![npm](https://img.shields.io/npm/v/datachannel.svg)](https://npmjs.org/package/datachannel) [![downloads](https://img.shields.io/npm/dm/datachannel.svg)](https://npmjs.org/package/datachannel) [![Build Status: Linux](https://travis-ci.org/muaz-khan/DataChannel.png?branch=master)](https://travis-ci.org/muaz-khan/DataChannel)

Github (open-sourced): https://github.com/muaz-khan/DataChannel

* [DataChannel basic demo](https://www.webrtc-experiment.com/DataChannel/)
* [Auto Session Establishment and Users presence detection](https://www.webrtc-experiment.com/DataChannel/auto-session-establishment.html)
* [Text Chat using Pusher and DataChannel.js](http://webrtc-chat-demo.pusher.io/)

# MultiRTC | Skype-like Demo Application

Github (open-sorced): https://github.com/muaz-khan/MultiRTC

* MultiRTC Firebase: [![npm](https://img.shields.io/npm/v/multirtc-firebase.svg)](https://npmjs.org/package/multirtc-firebase) [![downloads](https://img.shields.io/npm/dm/multirtc-firebase.svg)](https://npmjs.org/package/multirtc-firebase)
* MultiRTC WebSockets: [![npm](https://img.shields.io/npm/v/multirtc-websocket.svg)](https://npmjs.org/package/multirtc-websocket) [![downloads](https://img.shields.io/npm/dm/multirtc-websocket.svg)](https://npmjs.org/package/multirtc-websocket)
* MultiRTC Socketio: [![npm](https://img.shields.io/npm/v/multirtc.svg)](https://npmjs.org/package/multirtc) [![downloads](https://img.shields.io/npm/dm/multirtc.svg)](https://npmjs.org/package/multirtc)

# XHR-Signaling

XHR/XMLHttpRequest based WebRTC signaling implementation.

Github (open-sourced): https://github.com/muaz-khan/XHR-Signaling

# PluginRTC | IE/Safari Plugins compatible WebRTC-Experiments

Github (open-sourced): https://github.com/muaz-khan/PluginRTC

# ASP.NET MVC based WebRTC Demo

A simple WebRTC one-to-one demo written in September, 2012! It supports public rooms as well as password-protected private rooms! MS-SQL database is used as signaling gateway!

Github (open-sourced): https://github.com/muaz-khan/WebRTC-ASPNET-MVC

# WebSync-Signaling

WebSync is used as signaling gateway with/for WebRTC-Experiments e.g. RTCMultiConnection.js, DataChannel.js, Plugin-free screen sharing, and video conferencing.

Github (open-sourced): https://github.com/muaz-khan/WebSync-Signaling

# Server Sent Events (SSE) over PHP

Server Sent Events (SSE) are used to setup WebRTC peer-to-peer connections.

Github (open-sourced): https://github.com/muaz-khan/RTCMultiConnection/tree/master/demos/SSEConnection

# SignalR

SignalR project for RTCMultiConnection: https://github.com/muaz-khan/RTCMultiConnection-SignalR

* https://github.com/muaz-khan/WebRTC-Experiment/blob/master/Signaling.md#how-to-use-signalr-for-signaling

# SdpSerializer

SdpSerializer.js — An easiest way to modify SDP. It is an object-oriented way of sdp declaration, manipulation and serialization.

Github (open-sourced): https://github.com/muaz-khan/SdpSerializer

# Important [Experiments](https://github.com/muaz-khan/WebRTC-Experiment)

| Experiment Name        | Short Description           | Source | Demo |
| ------------- |-------------|-------------|-------------|
| `Pre-recorded Media Streaming` | Stream video files in realtime; same like webcam streaming! | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/Pre-recorded-Media-Streaming) | [Demo](https://www.webrtc-experiment.com/Pre-recorded-Media-Streaming/) |
| `Part of Screen Sharing` | Share a region of the screen; not the entire screen! | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/part-of-screen-sharing) | [Demo](https://www.webrtc-experiment.com/part-of-screen-sharing/) |
| `Plugin-free Screen Sharing` | Share the entire screen | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/Pluginfree-Screen-Sharing) | [Demo](https://www.webrtc-experiment.com/Pluginfree-Screen-Sharing/) |
| `One-Way Broadcasting` | Same like radio stations; transmit audio/video/screen streams in one-way direction. Though, it is browser-to-browser streaming! | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/webrtc-broadcasting) | [Demo](https://www.webrtc-experiment.com/webrtc-broadcasting/) |

# Useful [Experiments](https://github.com/muaz-khan/WebRTC-Experiment)

| Experiment Name        | Previous Demos           | New Demos |
| ------------- |-------------|-------------|
| **video-conferencing** / multi-user (group) video sharing | [Demo](https://www.webrtc-experiment.com/video-conferencing/) / [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/video-conferencing) | [Demo](https://www.webrtc-experiment.com/meeting/) / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/meeting) |
| **file sharing** / multi-user (group) files hangout | [Demo](https://www.webrtc-experiment.com/file-hangout/) / [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/file-hangout) | [Demo](https://www.webrtc-experiment.com/file-sharing/) / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/file-sharing) |
| **file sharing using SCTP data channels** | [Demo](https://www.webrtc-experiment.com/WebRTC-File-Sharing/) / -- | -- / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/WebRTC-File-Sharing) |
| **text chat** / multi-user (group) text chat | [Demo](https://www.webrtc-experiment.com/chat-hangout/) / [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/chat-hangout) | [Demo](https://www.webrtc-experiment.com/text-chat/) / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/text-chat) |
| **MultiRTC** | [Demo](https://www.webrtc-experiment.com/RTCMultiConnection/MultiRTC/) / -- | -- / [Source Code](https://github.com/muaz-khan/MultiRTC) |

# One-to-Many style of WebRTC [Experiments](https://github.com/muaz-khan/WebRTC-Experiment)

| Experiment Name        | Previous Demos           | New Demos |
| ------------- |-------------|-------------|
| **video-broadcasting** | [Demo](https://www.webrtc-experiment.com/broadcast/) / [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/broadcast) | [Demo](https://www.webrtc-experiment.com/one-to-many-video-broadcasting/) / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/one-to-many-video-broadcasting) |
| **audio-broadcasting** | [Demo](https://www.webrtc-experiment.com/audio-broadcast/) / [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/audio-broadcast) | [Demo](https://www.webrtc-experiment.com/one-to-many-audio-broadcasting/) / [Source Code](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/one-to-many-audio-broadcasting) |

# One-to-One Audio Calls

| Experiment Name        | Demo           | Source Code |
| ------------- |-------------|-------------|
| One-to-one WebRTC video chat using WebSocket | [Demo](https://www.webrtc-experiment.com/websocket/) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/websocket) |
| One-to-one WebRTC video chat using socket.io | [Demo](https://www.webrtc-experiment.com/socket.io/) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/socket.io) |
| WebRTC 1-1 Audio/Video/Screen Sharing | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/realtime-pluginfree-calls) | [Demo](https://www.webrtc-experiment.com/realtime-pluginfree-calls/) |
| WebRTC 1-1 Calls | [Source](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/realtime-pluginfree-calls) | [Demo](https://www.webrtc-experiment.com/realtime-pluginfree-calls/) |

# Single-Page / One-Page / Client Side

| Experiment Name        | Demo           | Source Code |
| ------------- |-------------|-------------|
| **Switch streams from screen-sharing to audio+video. (Renegotiation)** | [Demo](https://www.webrtc-experiment.com/demos/switch-streams.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/switch-streams.html) |
| **Share screen and audio/video from single peer connection!** | [Demo](https://www.webrtc-experiment.com/demos/screen-and-video-from-single-peer.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/screen-and-video-from-single-peer.html) |
| **Text chat using RTCDataChannel APIs** | [Demo](https://www.webrtc-experiment.com/demos/client-side-datachannel.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/) |
| **Simple video chat** | [Demo](https://www.webrtc-experiment.com/demos/client-side.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/client-side.html) |
| **Sharing video - using socket.io for signaling** |[Demo](https://www.webrtc-experiment.com/demos/client-side-socket-io.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/client-side-socket-io.html) |
| **Sharing video - using WebSockets for signaling** | [Demo](https://www.webrtc-experiment.com/demos/client-side-websocket.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/client-side-websocket.html) |
| **Audio Only Streaming** | [Demo](https://www.webrtc-experiment.com/demos/audio-only-streaming.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/audio-only-streaming.html) |
| **MediaStreamTrack.getSources** | [Demo](https://www.webrtc-experiment.com/demos/MediaStreamTrack.getSources.html) | [Source](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/demos/MediaStreamTrack.getSources.html) |

# [Documents for newcomers/newbies/beginners](https://www.webrtc-experiment.com/docs/)

| A few documents for newbies and beginners        |
| ------------- |
| [How to use RTCPeerConnection.js?](https://www.webrtc-experiment.com/docs/how-to-use-rtcpeerconnection-js-v1.1.html) |
| [RTCDataChannel for Beginners](https://www.webrtc-experiment.com/docs/rtc-datachannel-for-beginners.html) |
| [How to use RTCDataChannel?](https://www.webrtc-experiment.com/docs/how-to-use-rtcdatachannel.html) - single code for both canary and nightly |
| [WebRTC for Beginners: A getting stared guide!](https://www.webrtc-experiment.com/docs/webrtc-for-beginners.html) |
| [WebRTC for Newbies ](https://www.webrtc-experiment.com/docs/webrtc-for-newbies.html) |
| [How to switch streams?](https://www.webrtc-experiment.com/docs/how-to-switch-streams.html) |
| [How to echo cancellation? / Noise management?](https://www.webrtc-experiment.com/docs/echo-cancellation.html) |
| [STUN or TURN? Which one to prefer; and why?](https://www.webrtc-experiment.com/docs/STUN-or-TURN.html) |
| [WebRTC RTP Usage](https://www.webrtc-experiment.com/docs/RTP-usage.html) |
| [webrtcpedia!](https://www.webrtc-experiment.com/webrtcpedia/) |
| [Are you want to learn WebRTC?](http://muaz-khan.blogspot.com/2013/12/i-want-to-learn-webrtc.html) |
| [WebRTC Tips & Tricks](http://muaz-khan.blogspot.com/2014/05/webrtc-tips-tricks.html) |
| [WebRTC for ASP.NET developers](https://muaz-khan.blogspot.com/2014/10/webrtc-for-aspnet-developers.html) |
| [Write Screen Sharing Application for Your Own WebSite](https://muaz-khan.blogspot.com/2017/08/write-screen-sharing-application-for.html) |
| [RecordRTC and Upload to PHP Server](https://muaz-khan.blogspot.com/2017/08/recordrtc-and-upload-to-php-server.html) |
| [Take photo from a webcam using JavaScript](https://muaz-khan.blogspot.com/2017/07/take-photo-from-webcam-using-javascript.html) |
| [WebRTC captureStream API](https://muaz-khan.blogspot.com/2017/04/webrtc-capturestream-api.html) |
| [Disable ICE Trickling](https://muaz-khan.blogspot.com/2015/01/disable-ice-trickling.html) |
| [I want to learn WebRTC!](https://muaz-khan.blogspot.com/2013/12/i-want-to-learn-webrtc.html) |

1. http://muaz-khan.blogspot.com/search/label/WebRTC
2. https://www.webrtc-experiment.com/#documentations
3. https://www.facebook.com/WebRTC
4. https://plus.google.com/+WebRTC-Experiment/posts

# Custom Signaling

1. [Socket.io over Node.js](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/socketio-over-nodejs)
2. [WebSocket over Node.js](https://github.com/muaz-khan/WebRTC-Experiment/blob/master/websocket-over-nodejs)
3. [WebSync / ASP.NET MVC](https://github.com/muaz-khan/WebSync-Signaling)
4. [XHR Signaling](https://github.com/muaz-khan/XHR-Signaling)
5. [openSignalingChannel](http://www.rtcmulticonnection.org/docs/openSignalingChannel/)

## Signaling?

* https://github.com/muaz-khan/WebRTC-Experiment/blob/master/Signaling.md

# Browser Support

[WebRTC Experiments](https://www.webrtc-experiment.com/) works fine on following web-browsers:

| Browser        | Support           |
| ------------- |-------------|
| Firefox | Windows, Mac, Ubuntu, Android |
| Google Chrome | Windows, Mac, Ubuntu, Android, Chrome OS |
| Opera | [Windows, Mac, Ubuntu, Android  |
| Edge | Windows 10+ |
| Safari 11 | Mac OSX, iOS 10+, iphone/ipad |

and Cordova/ionic/phonegap/electron/node-webkit/etc apps.

# RTCMultiConnection Wiki Pages

* [Select Camera and Microphone Devices](https://github.com/muaz-khan/RTCMultiConnection/wiki/Select-Camera-and-Microphone-Devices)
* [Fix Duplicate Videos Issues](https://github.com/muaz-khan/RTCMultiConnection/wiki/Fix-Duplicate-Videos-Issues)
* [List of Breaking Changes](https://github.com/muaz-khan/RTCMultiConnection/wiki/Breaking-Changes)
* [Coding Tricks](https://github.com/muaz-khan/RTCMultiConnection/wiki/Coding-Tricks)
* [Switch Between Cameras](https://github.com/muaz-khan/RTCMultiConnection/wiki/Switch-between-cameras)
* [Bandwidth Management](https://github.com/muaz-khan/RTCMultiConnection/wiki/Bandwidth-Management)
* [Channels and Sessions Management](https://github.com/muaz-khan/RTCMultiConnection/wiki/Channels-and-Sessions)
* [How to send Custom/Private messages?](https://github.com/muaz-khan/RTCMultiConnection/wiki/Custom-Messages)
* [Custom Private Servers](https://github.com/muaz-khan/RTCMultiConnection/wiki/Custom-Private-Servers)
* [How to link RTCMultiConnection.js?](https://github.com/muaz-khan/RTCMultiConnection/wiki/How-to-link-RTCMultiConnection.js%3F)
* [How to fix echo?](https://github.com/muaz-khan/RTCMultiConnection/wiki/How-to-fix-echo%3F)
* [How to share Part-of-Screen?](https://github.com/muaz-khan/RTCMultiConnection/wiki/Part-of-Screen-Sharing)
* [How to detect Presence of the users & sessions?](https://github.com/muaz-khan/RTCMultiConnection/wiki/Presence-Detection)
* [How to share screen?](https://github.com/muaz-khan/RTCMultiConnection/wiki/Screen-Sharing)
* [How to secure your RTCMultiConnection codes?](https://github.com/muaz-khan/RTCMultiConnection/wiki/Security)
* [Use WebSync Signaling Server in any RTCMultiConnection demo](https://github.com/muaz-khan/RTCMultiConnection/wiki/WebSync-Signaling-Server)
* [How to implement client-side (local) screen-sharing without involving any 3rd-party service or extension or addon](https://github.com/muaz-khan/RTCMultiConnection/wiki/Screen-Sharing-on-your-Local-Server)
* [Detect Who is Speaking](https://github.com/muaz-khan/RTCMultiConnection/wiki/Detect-Who-is-Speaking)
* [RTCMultiConnection StreamID](https://github.com/muaz-khan/RTCMultiConnection/wiki/RTCMultiConnection-StreamID)
* [checkPresence and automatically join rejoin rooms](https://github.com/muaz-khan/RTCMultiConnection/wiki/checkPresence-and-automatically-join-rejoin-rooms)
* [WebRTC Data Channels Latency Detection](https://github.com/muaz-khan/RTCMultiConnection/wiki/WebRTC-Data-Channels-Latency-Detection)
* [How to remove video on user left](https://github.com/muaz-khan/RTCMultiConnection/wiki/How-to-remove-video-on-user-left)

# RecordRTC Wiki Pages

1. [PHP Upload Issues](https://github.com/muaz-khan/RecordRTC/wiki/PHP-Upload-Issues)
2. [Get Synced WAV WebM](https://github.com/muaz-khan/RecordRTC/wiki/Get-Synced-WAV-WebM)
3. [Ffmpeg](https://github.com/muaz-khan/RecordRTC/wiki/Ffmpeg)
4. [Upload to YouTube](https://github.com/muaz-khan/RecordRTC/wiki/Upload-to-YouTube)
5. [Upload to Server](https://github.com/muaz-khan/RecordRTC/wiki/Upload-To-Server)
6. [RecordRTC on AngularJs](https://github.com/muaz-khan/RecordRTC/wiki/RecordRTC-on-AngularJs)
7. [Record Multiple Streams Into Single File](https://github.com/muaz-khan/RecordRTC/wiki/Record-Multiple-Streams-Into-Single-File)

# Other Wiki Pages

* [WebRTC DataChannel and Firefox](https://github.com/muaz-khan/WebRTC-Experiment/wiki/WebRTC-DataChannel-and-Firefox)
* [Broadcasting Demos](https://github.com/muaz-khan/WebRTC-Experiment/wiki/Broadcasting-Demos)
* [mozAV2AudioOnly](https://github.com/muaz-khan/WebRTC-Experiment/wiki/mozAV2AudioOnly)
* [RTCDataConnection](https://github.com/muaz-khan/WebRTC-Experiment/wiki/RTCDataConnection)
* [RTCMultiConnection v1.0](https://github.com/muaz-khan/WebRTC-Experiment/wiki/RTCMultiConnection)
* [RTCPeerConnection Documentation](https://github.com/muaz-khan/WebRTC-Experiment/wiki/RTCPeerConnection-Documentation)

# Credits

* Muaz Khan - https://github.com/muaz-khan

# License

All [WebRTC Experiments](https://github.com/muaz-khan/WebRTC-Experiment) are released under [MIT licence](https://www.webrtc-experiment.com/licence/) . Copyright (c) [Muaz Khan](http://www.muazkhan.com/).
