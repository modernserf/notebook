---
layout: post
title: Stateless
---

I've been making client-heavy web applications for about eight years now, which is now approximately half of the time that pattern has existed (beginning with GMail in 2004). I'm still not 100% sure they're a good idea.

On one hand, I am unambiguously pro-web as a platform for software distribution. Putting aside whether the web allows for _good_ software, you can run web apps on just about any computer, you can usually run them in a matter of seconds, and -- given the App Store model that dominates mobile and is slowly taking over desktop -- it will soon be one of the only free-as-in-speech software ecosystems.

On the other hand, browsers are pretty shit at providing native-like app experiences, particularly on mobile. At best you get an app that's ravenously RAM-hungry and has an Uncanny Valley-resemblance to native apps. Nobody makes a web app because they think it will be _better_ than a native app; they make the web app because the alternative is no app at all.

The root of my discomfort, I think, is that so much of the web software I have written has been a futile attempt to simulate the feel of native apps. I'm not talking about stuff like Electron, Cordova, React Native, etc -- I've never even used them -- I mean at a much lower level: modals, tooltips, notifications, dropdowns. In other words: interactivity & state.

I recognize that this is a pretty extreme position to take; after all, half of these have been a part of the web since the DHTML era and have established web-first design patterns associated with them. But I think the early introduction of non-navigational interactivity stunted the development of the web as its own medium, just as the introduction of "talkies" stunted the development of film as a visual medium.
