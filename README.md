# 1. element-ui_select

Element-UI Select下拉框点击事件不触发问题解决方法

@click事件换成@click.native就可以了


# 2. select下拉框出现/隐藏时触发

@visible-change  select下拉框出现/隐藏时触发。默认参数是点击时展开为true，关闭为false。

显示的是label，获取的是value，绑定的是选中的内容的value

```
// @visible-change='changeFunc'
changeFunc(val){  
  if(val==true){
    alert("下拉已展开")
  }else{
    alert("下拉已隐藏")
  }
} 
```
