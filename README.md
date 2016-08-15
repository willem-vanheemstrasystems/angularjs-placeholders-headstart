# angularjs-placeholders-headstart
AngularJS Placeholders - Headstart

Based on 'Placeholders' at http://ngbp.github.io/ngbp/#/about

#Placeholders

Angular Placeholders is a simple library for mocking up text and images. You can automatically throw around some "lorem ipsum" text:

```javascript
<p ph-txt="3s"></p>
```

Which gives you this:

```javascript
<p>
Eu sem integer vitae justo eget magna fermentum iaculis eu non diam. Vestibulum rhoncus est pellentesque elit ullamcorper dignissim cras tincidunt lobortis feugiat vivamus at augue eget. Sed cras ornare arcu dui.

</p>
```

Even more exciting, you can also create placeholder images, entirely client-side! For example, this:

```javascript
<img ph-img="50x50" />
<img ph-img="50x50" class="img-polaroid" />
<img ph-img="50x50" class="img-rounded" />
<img ph-img="50x50" class="img-circle" />
```

Gives you this:

50x50  50x50  50x50  50x50

Which is awesome.
