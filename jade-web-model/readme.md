#model说明
###适用于web前端开发（静态页面部分），html，css，js三者分离。细分开发。
####model目录（暂定）
- src/    *引用文件*
  - fonts/
  - imgs/
- script/ *所有脚本文件*
  - js/
  - script.jade   *里边放增加的js文件引用*
- style/  *所有样式文件*
  - css/          *所有css*
    - componets/      *放一些css组件*
    - public/         *放一些公共css代码*
    - header.css      *整个页面header部分css*     
    - container.css   *整个页面container部分css*
    - footer.css      *整个页面footer部分css*
  - layout/       *可能需要*
  - style.jade    *所有样式jade文件*
- views/  *所有视图布局和html文件*||*都是骨架般固定的值，需要修改的部分可能只存在于head部分，也可以保持原状，在app.jade主文件中添加*
  - layout/       *视图布局文件*
    - head.jade       *视图布局head部分*||*可能有修改*
    - body.jade       *视图布局body部分*
    - layout.jade     *视图布局主文件*
  -header.jade    *头部区域html文件*
  -container.jade *内容区域html文件*
  -footer.jade    *底部区域html文件*
- app.jade *页面主文件*
