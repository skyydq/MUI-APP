# NanBei-HanduAPP

请在手机上演示，具体打包方法请百度。。。

一个办公及图片采集的APP，用于对产品的图片拍照描述，产品审批及质检流程。
使用DCloud的产品（MUI）制作，包括首页，审批，质检单，个人设置四个模块。我负责整个项目的技术选型，制作和调试以及机型适配。项目中主要难度是各种机型的适配，
下拉刷新，图片库瀑布流布局，侧滑菜单和下拉刷新的兼容问题以及手势码设置。机型适配IOS没大问题基本实现需求，安卓机主要是流畅性问题，我给页面开启了硬件加速，并优化DOM
结构和代码合并减少冗余；下拉刷新则是使用了插件（mescroll.js）以实现自定义样式;图片库瀑布流布局我定了2个列，动态添加列表的时候对着2个列作比较，将新的
列表项加到高度低的列中去，这样就实现了瀑布流布局；侧滑菜单则是使用了官网的结构实现，和下拉刷新的兼容则是和原作者进行了讨论，后来知道是两个类的冲突，我选择
使用了mesroll.js插件的类解决了这个小BUG。至此，APP的开发工作完成@！

------觉得有用请给我个star！------
