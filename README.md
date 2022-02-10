## Skrollr - Parallax Scrolling

#### 기본 사용법
```html
<div data-0="color:rgb(0,0,0)" data-500="color:rgb(255,255,255)"></div>
```
```javascript
<script src="skrollr.min.js"></script>
<script>
    const s = skrollr.init();
</script>
```
브라우저 기준 ABSOLUTE.
- data-start => scrolled to the top of the document
- data-100-start => after scrolling down 100px
- data-end => at the bottom of the document
- data-100-end => 100px before the bottom of the document
- data-100 => same as data-100-start
---
---
엘리먼트 기준 RELATIVE.
- data-top => top of an element = top of the browser
- data-100-top => top of an element = 100px below the top of the browser
- data--100-top => top of element = 100px above the top of the browser
- data-bottom => bottom of element = bottom of browser
- data-100-bottom => bottom of element = 100px below bottom of browser
- data--100-bottom => bottom of element = 100px above bottom of browser
- data-center => element vertically centered in browser
- data-[browserPosition]-[elementPosition] (e.g., data-center-top)
---
---
##### 사이트 보기 [Click](https://franz0406.github.io/Parallax-Scrolling/).