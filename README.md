# storyBoradSplit

##storyBorad拆分
---
*1.选中要进行分割出去的viewcontrollers
*2.选择 Editor > Refactor to Storyboard.
*注：此时会生成一个新的storyborad。 如果选中的viewcontrollers在原有storybord中有引用，则会在原来的storyborad中生成相应的storyborad Reference，相应的引用连线会指向相应的storyborad Reference


##不同storyborad中连线引用
---
*1.在被引用的storyBorad中找到被引用的viewcontroller添加storyborad id 并勾选使用storyborad id 选项
*2.在引用使用的storyBorad中添加storyborad Reference对象实例，这个对象有3个属性，storyborad(被引用的storyBorad名称)，referenced ID（被引用的viewController的storyborad id）, bundle（被引用storyborad的路径，如果路径和main。storyBorad路径相同，可以不填）,
*3.将连线连向storyborad Reference。
