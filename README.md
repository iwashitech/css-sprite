# CSSスプライト作業手順

## スプライトで使用するspanについて

### spanの必要性（aタグだけではダメ？）
- aタグの中に他のタグが入っていた場合にspanがどうしても必要
- spanがimgタグの代わり
- 一貫性（ややこしいので理解しやすい）
### spanタグのafterの意味
- spanタグが親要素
- spanタグ内に子孫要素として不要なタグを使用しないようにするためafterを使用

## 参考ページ

- レスポンシブWebデザインでハマりがちな%指定
http://design-spice.com/2014/03/24/percentag/
- css - responsive sprites / percentages - Stack Overflow
http://stackoverflow.com/questions/21810262/responsive-sprites-percentages#answer-23419418

- Responsive CSS Sprites
⇒background-positionの計算方法、background-sizeの計算方法
http://www.browniesblog.com/A55CBC/blog.nsf/dx/responsive-css-sprites.html
- Can spritesmith generate responsive sprites? · Issue #32 · twolfson/gulp.spritesmith
https://github.com/twolfson/gulp.spritesmith/issues/32
http://www.lorenzomarcon.com/2014/12/responsive-css-sprites/

### アスペクト比関係のページ

- CSSだけでアスペクト比を固定するテク
http://qiita.com/ryounagaoka/items/a98f59347ed758743b8d
- html - Maintain the aspect ratio of a div with CSS - Stack Overflow
http://stackoverflow.com/questions/1495407/maintain-the-aspect-ratio-of-a-div-with-css#answer-10441480
- javascript - Height equal to dynamic width (CSS fluid layout) - Stack Overflow
http://stackoverflow.com/questions/5445491/height-equal-to-dynamic-width-css-fluid-layout#answer-6615994
- Responsive background images with fixed or fluid aspect ratios
http://voormedia.com/blog/2012/11/responsive-background-images-with-fixed-or-fluid-aspect-ratios
- アスペクト比 【 aspect ratio 】 縦横比":http://e-words.jp/w/%E3%82%A2%E3%82%B9%E3%83%9A%E3%82%AF%E3%83%88%E6%AF%94.html
```
アスペクト比とは、画面や画像の縦と横の長さ（ピクセル数）の比。
一般的には「横：縦」と表記する。
```
