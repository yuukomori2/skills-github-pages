---
title: Welcome to my blog!
---
# レベル 1 の見出し
<img alt="曇りの朝" src="https://octodex.github.com/images/cloud.jpg"
 width="100" align="right">
## レベル 2 の見出し①
## レベル 2 の見出し②
- [ ] トピックのアイデアについて[github ブログ](https://github.blog/) で確認する。
- [ ] [GitHub Pages](https://skills.github.com/#first-day-on-github) について学習する。
- [ ] 最初のブログ投稿を実際のウェブページに変換する。

[ffmpeg](https://www.ffmpeg.org)を使用して画像またはビデオをダークモードからライトモードに変換する
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
