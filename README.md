# laydate-extendBtn
扩展laydate增加自定义范围选择按钮，替换laydata.js文件，引入css，图片路径自己看着整整吧，自己扩展也行
# Quick Start
```
laydate.render({
        elem: '#id', //指定元素
        theme: 'extbtn',
        type: 'datetime',
        range:true,
        btns: ['clear', 'confirm','now'],
        extrabtns: [
            {id:'threeMonth', text:'近三月'},
            {id:'oneYear', text:'近一年'},
            {id:'threeYear', text:'近三年'},
            {id:'fiveYear', text:'近五年'},
            {id:'tenYear', text:'近十年'}
        ],

    });
```
#style
![](https://upload-images.jianshu.io/upload_images/13800756-d301ad02584a902c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/665/format/webp)
