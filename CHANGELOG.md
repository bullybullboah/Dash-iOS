# Master

* No changes yet.

# 1.8.0

* Fixed docset index page button on iOS 11 - [7fd09e8](https://github.com/Kapeli/Dash-iOS/commit/7fd09e8cae3b981aa75662ef3d19111a3ab2039a)
* Fixed an issue which caused the Swift docset to still appear in Dash, although it was removed - [ca9c9f6](https://github.com/Kapeli/Dash-iOS/commit/ca9c9f64daf9eac30c4dcc000f99240a424bb123)
* Fixed an issue which caused the search results table to be inset on iOS 11 - [d022d88](https://github.com/Kapeli/Dash-iOS/commit/d022d888e21a37e54a9960239689cac54bb7ef5b)
* Fixed an issue which caused search results to not be highlighted correctly - [aea602e](https://github.com/Kapeli/Dash-iOS/commit/aea602e9b5292c110f6cb934f892349a3290689d)
* Fixed access to UI on background thread - [90b1875](https://github.com/Kapeli/Dash-iOS/commit/90b1875f3728f5ca4485693ec8209cf8342cecfe)
* Fixed an issue which caused extra table row separators to appear above the search results table - [313893d](https://github.com/Kapeli/Dash-iOS/commit/313893ddeddb10b029d7bb2c324867a09a127946)
* Fixed Settings button sometimes appearing faded - [2bb42fe](https://github.com/Kapeli/Dash-iOS/commit/2bb42fe2ee51a3fabadb921100da6b0c7674efbc)
* Consolidated the OpenCV C, C++, Python and Java docsets into a single OpenCV docset - [9af12ee](https://github.com/Kapeli/Dash-iOS/commit/9af12ee33f4d60de14d4bbb0a0741be61296e2b0)

# 1.7.0

* Added support for adding docsets using the "Open in..." menu. Thanks to [@insightmind](https://github.com/insightmind) for the great work on this - [#52](https://github.com/Kapeli/Dash-iOS/pull/52)
* Added Java SE9 docset - [7c727c2](https://github.com/Kapeli/Dash-iOS/commit/7c727c2d30d41c0f37a4588510a804e4300b8c61)
* Added Java EE8 docset - [61e2df7](https://github.com/Kapeli/Dash-iOS/commit/61e2df74f955bcf22ff6611be1ff0f6e45f6024a)
* Added AngularJS docset (now separate from the Angular docset) - [b0ef193](https://github.com/Kapeli/Dash-iOS/commit/b0ef1936b71b026baa92e76371331be26c1f32dd)
* Removed Swift docset. Swift docs can be found in the Apple API Reference docset - [88913a6](https://github.com/Kapeli/Dash-iOS/commit/88913a6236c8c3c3874da63b300930496658637e)
* Fixed an AirDrop issue. Thanks to [@ClementPadovani](https://github.com/ClementPadovani) for the fix - [#61](https://github.com/Kapeli/Dash-iOS/pull/61)
* Added Glossary, Control Structure, Expression, Handler, Iterator, Widget, Block, Template types - [a94006b](https://github.com/Kapeli/Dash-iOS/commit/a94006bc39996c69d168f9c2d8f94b0e37c31ac6)

# 1.6.3

* Fixed an iPad-only crash which occurred in Settings while going into split view mode with the search field active - [36cf36d](https://github.com/Kapeli/Dash-iOS/commit/36cf36df40619ebfae903e39af4ea836e26fdc42)

# 1.6.2

* Fixed an issue which caused the iOS remote feature to sometimes not pair correctly - [9f9dd6c](https://github.com/Kapeli/Dash-iOS/commit/9f9dd6c8b5761b28899dcae01f828888ab9011d8)
* Consolidated all Angular docsets into one - [56fda1b](https://github.com/Kapeli/Dash-iOS/commit/56fda1b4fa94fa910e377004ba7988ecc5e389eb)
* Fixed an issue which caused empty rows to sometimes appear in the table of contents - [097197c](https://github.com/Kapeli/Dash-iOS/commit/097197c828db9e1b1524f46da41a0db92e7376cf)
* Fixed an iPad-only crash which occurred in Settings while pressing Done with the search field active - [e87a069](https://github.com/Kapeli/Dash-iOS/commit/e87a069b6a94f31d9fac91be9ac6ca4569bcf251)
* Fixed an issue in the User Contributed repo which caused author names to not be truncated when there's not enough space - [3482d8f](https://github.com/Kapeli/Dash-iOS/commit/3482d8f7cd0f6e19b1a42c80a69f09783565522a)
* Added "Data Source" type - [6a45537](https://github.com/Kapeli/Dash-iOS/commit/6a45537447319a68341c2b4686da3b4753828310)

# 1.6.1

* Added support for receiving docsets using AirDrop. Thanks to [@vinayjn](https://github.com/vinayjn) for the great work on this - [#36](https://github.com/Kapeli/Dash-iOS/pull/36)
* Added Pug docset. Removed Jade docset - [36fdff3](https://github.com/Kapeli/Dash-iOS/commit/36fdff3a2ac6d74bddb07ef8c430d46b19dd64d3)
* Fixed build products path. Thanks to [@RegalMedia](https://github.com/RegalMedia) for reporting the issue - [#28](https://github.com/Kapeli/Dash-iOS/issues/28)
* Fixed the display of included modules for Ruby docsets - [4416ccb](https://github.com/Kapeli/Dash-iOS/commit/4416ccbb7b78b0b4b0e72608f1ce5bd38a013b72)
* Fixed Dash App Store display/product name - [5015177](https://github.com/Kapeli/Dash-iOS/commit/5015177c23cefaea0688db95b462b33705e12952)

# 1.6.0

* Added support for cheat sheets - [#22](https://github.com/Kapeli/Dash-iOS/pull/22)
* Added support for user contributed docsets - [#20](https://github.com/Kapeli/Dash-iOS/pull/20)
* Added state restoration support. Thanks to [@zhongwuzw](https://github.com/zhongwuzw) for the great work on this - [#18](https://github.com/Kapeli/Dash-iOS/pull/18)
* Fixed Unity 3D docset bug which caused it to not remember the selected language. Thanks to [@hantengx](https://github.com/hantengx) for reporting the issue - [#17](https://github.com/Kapeli/Dash-iOS/issues/17)
* Fixed a crash in the docset downloader. Thanks to [@zhongwuzw](https://github.com/zhongwuzw) for the fix - [#16](https://github.com/Kapeli/Dash-iOS/pull/16)
* Stopped an evil `if()` from taking over the world. Thanks to [@BalestraPatrick](https://github.com/BalestraPatrick) for reporting the issue and [@flovilmart](https://github.com/flovilmart) for fixing it - [#4](https://github.com/Kapeli/Dash-iOS/pull/4)
