# width-auto-overflow

div宽度不确定，超出...

最好不要设置高度，设置line-height既可

```css
    .main{
        overflow: hidden;
        text-overflow: ellipsis;
        display: -webkit-box;
        -webkit-line-clamp: 1;
        -webkit-box-orient: vertical;
    }
```
如果想在第二行超出...
将 -webkit-line-clamp: 1;值改为2
