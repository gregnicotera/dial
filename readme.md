## About

Dial is a (beta) Chrome Extension. It's a launcher of frequent websites that you define.
It replaces the newtab page on Chrome.

If you want to check how it works, check out this demo:

[Demo](http://singuerinc.github.io/dial/)

## Search
![search](https://dl.dropboxusercontent.com/u/311265/dial/search_anim.gif)

> Tip: Search and press enter: navigates to the first occurrence.

## Themes
### Dark
![dark](https://dl.dropboxusercontent.com/u/311265/dial/theme_dark.png)

### Light
![light](https://dl.dropboxusercontent.com/u/311265/dial/theme_light.png)

## Installation
If you want to test Dial you have to install it manually in Chrome.

1. Clone/Download the repo
2. Go to [Chrome extensions settings](chrome://extensions/)
3. Click on "Load unpacked extension..."
4. Select the folder that contains Dial files.
5. Open a new tab in Chrome.

## develop

```sh
# compile js
watchify -t vueify -e _src/main.js -o build.js
```

### TODO
- [x] Navigate through results with keys
- [ ] Options page
- [ ] Add/Edit/Remove links
- [ ] Profile image upload
- [x] Sync
- [ ] Backgrounds?
- [ ] Fonts
- [ ] Language Flags
- [ ] Themes
- [ ] Dropify for profile image
- [ ] copyright - open source page
- [ ] Drag & drop in edit mode with dragula
