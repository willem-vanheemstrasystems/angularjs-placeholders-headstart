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

![Image](../blob/master/public_html/img/nokia.png?raw=true)

<img ph-img="50x50" class="ng-isolate-scope" title="50x50" alt="50x50" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAACf0lEQVRoQ+1VC4txURRdIibjNYWIvCITyqPm//8B78R4JOQ1GpciQpj2KZpR5n7OzCnNd06pG866ez323hpFUY74A0cjidyZi9KROzME0hHpiCAFZLQECcsNKx3hlk7QRemIIGG5YaUj3NIJuigdESQsN+z/5Ui320Wz2fyiVjgcRiAQwPv7O+r1OtbrNQwGA4LBILxer6qyv435T45UKhVMJhPEYjG4XK5zkbvdDtlsFsfjEalUCq+vr1gul0gmk7Bard+S+W1MVSJUbC6Xw2azQSaTgdlsPhc4Ho9Rq9XgdDoRj8fR6XTQarXg9/sRiUSuEhGBqUqEFM7n86CX09FoNHC73YhGo+j1el8KPxFzOBywWCwsjkajkQlAz/Q73fX5fCgUCjdjJhKJq+KoEqFIUWQeHx9BQI1Gg8UsFAqxvhgOhzj1y4mIyWRixZdKJcxmM9jtdiiKgoeHBxbBxWLBhfny8sJP5PLm29sbqtUqixipfY0IvXQ+n6NcLmO73UKr1eL5+Zk58hPMa0xUHbm8SGpS1IgERehzT3yOFrlHQ6BYLGI6nTJHySWabD/B/DUip2JtNhtTl9yhZqfCT81OsaPPaDRiETocDowUjWVy5fLcgslNZDAYsD3x9PTExi/1CO0OeqYRS+7QuRy/er2eNTRNO9o3/X4f+/2eTTeKGg/mdyNdNVqkJk0c6gUqRKfTsaVHI5YO9QG5slqtzgvR4/Gw78gR2jtUfLvdZo5RxNLpNHu+BVNtyaoSUV3Rd/IHSeROjDiXIR2RjghSQEZLkLDcsNIRbukEXZSOCBKWG1Y6wi2doIvSEUHCcsNKR7ilE3RROiJIWG7YP+PIB17XeZP8OKTpAAAAAElFTkSuQmCC">

Which is awesome.
