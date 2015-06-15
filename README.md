各大浏览器 hack
==============

###Firefox 浏览器
```
@-moz-document url-prefix() {
  .selector {
    property: value;
  }
}
```

###支持所有Gecko内核的浏览器 (包括Firefox)
```
*>.selector { property: value; }
```

###Webkit 内核浏览器
```
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  Selector {
    property: value;
  }
}
```


###Opera 浏览器
```
html:first-child>b\ody Selector {property:value;}
```

##IE 浏览器

###IE 9
```
:root Selector {property: value\9;}
```

###IE 9-
```
Selector {property: value\9;}
```

###IE 8
```
Selector {property: value/;}
```
或：
```
@media \0screen {
    Selector {property: value;}
}
```

###IE 8+
```
Selector {property: value\0;}
```
###IE 7
```
*+html Selector{property:value;}
```
或：
```
*:first-child+html Selector {property:value;}
```
###IE 7-
```
Selector {*property: value;}
```
###IE6
```
Selector {
  _property: value;
}
```
或者： 
```
*html Selector {
  property: value;
}
```
