---
title: "Battery Status API が削除されました"
date: "2016-10-28T23:57:00-04:00"
categories: ["dom", "privacy-security"]
tags: []
versions: ["52"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1313580"
      title: "Bug 1313580 - Remove web content access to Battery API"
    - url: "https://groups.google.com/d/topic/mozilla.dev.platform/5U8NHoUY-1k/discussion"
      title: "Removing the Battery Status API?"
---
リモートの追跡者によってユーザーのフィンガープリンティングに使用される可能性があるといったプライバシー上の理由から、Firefox 52 以降 [Battery Status API](https://developer.mozilla.org/ja/docs/Web/API/Battery_Status_API) がウェブコンテンツから使用できなくなりました。正当な使用例が実際に存在していかどうかは不明です。
