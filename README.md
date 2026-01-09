经测试 ios/macos26 没有出现这个问题，17 版本有这个问题
18版本修复的
Fixed the Canvas drawImage() API to throw an exception when the image is in broken state. (128588063)
https://developer.apple.com/documentation/safari-release-notes/safari-18-release-notes
https://github.com/WebKit/WebKit/pull/29003
