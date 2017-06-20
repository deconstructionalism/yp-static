# yp-static
let's build the YallaPunk website styling!

### summary of changes added by Arjun 6/19/2017
- pages built so far:
  - front page
  - blog template (copied `about` page from wireframe)
- website container (`navbar`, `contents`, etc) resizes to 3 sizes with decreasing width:
  1) full width desktop viewing
  2) narrow desktop viewing
  3) mobile viewing  
- for views 2 and 3, logo floating in top-left corner becomes a mini-logo (stylized YP) on the `navbar`. I thought it might look good..thougts?
- SVG logos were simplified using [this](http://petercollingridge.appspot.com/svg-editor) so they could be styled with drop-shadow 
- just to make loading fonts less annoying while we are still using a separate page for each route, the webfonts are stored locally. eventually, we may want to switch back loading the fonts from Google using `<link>` in `head`
- to template out contents for other pages, simply replace `.temp-div` with the contents:
```html
...
<div id="contents">
    <div class="temp-div">ABOUT</div>
</div>
...
```



