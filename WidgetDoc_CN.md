WidgetDoc_CN.md

### What is widget.

 Widget就是小组件，在安卓平台和早期的Windsphone平台已发布多年。苹果于WWDC2020中iOS14推出。
 Widget在iOS系统是使用swiftUI由Widgetkit实现的。WidgetKit整合了iOS14之前系统在负一屏的Notification Center framework，也叫Today widgets。

### What widget can do.

Widget can show main app pivotal content in home screen that user can not open app.

### What is widget featrue.

Because of widget show in iOS home screen, if not limlit widget. The will cast lost battery and user may pay more attion in it. So apple limlit widget. The widget extension is not continually active, even if the widget is onscreen. The widget data reload most be more than 5 minutes. and not available any animations. Widgets present read-only information and don’t support interactive elements such as scrolling elements or switches.

### What widget can do for our app.

We can show all the device info (name, icon, featrue etc) that had connected. After add or remove device in app. Our developer can send the devices data to widget  [WidgetCent]. And can not reload data evert. But the battery not need to show. becaust widget can not to establish connection with the device. 
