tabbar 实现思路
1：如果在下方有一个单独的tabbar组件， 

​		自定义 tabbar , 在app 中使用。

​		让 tabbar 出于底部，并且设置相关的样式。

2：tabbar 中显示的内容有外界决定

​		定义插槽 		弹性布局平分 tabbar 

3：自定义 tabbarItem , 可以 传入图片 和 文字

​		定义 tabbaritem ,并且定义两个插槽 图片  文字

​		给两个插槽外层包装 div  用于设置样式

​		填充插槽 实现底部 tabbar 的效果