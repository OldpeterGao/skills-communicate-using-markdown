# Daily Learning

## Morning Planning
- [x] 1
- [ ] 学习 [GitHub Pages](https://skills.github.com/#first-day-on-github) 的使用方法  
- [ ] 将我的第一篇博客转换为网页形式

<!--
![](https://octodex.github.com/images/cloud.jpg)
-->

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">

## Review
使用 [ffmpeg](https://www.ffmpeg.org) 将图片或视频从深色模式转换为浅色模式

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
