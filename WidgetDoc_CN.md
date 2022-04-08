WidgetDoc_CN.md

### What is widget.

During WWDC 2020, Apple announced the [widget] for iOS (as well as iPadOS and MacOS). With the new [WidgetKit]framework, 

WidgetKit整合了iOS14之前系统在负一屏的Notification Center framework，也叫Today View. Widget are built entirely with SwiftUI. you can build widgets that can be added to your home screen to let you see important information at a glance. When they need more details, your widget takes them directly to the appropriate place in your app.

 A great widget is glanceable, it's relevant and it's personalized. This is very important, widgets are not mini-apps. Your can have it in three different sizes, small, medium or large.
  
 If you have amost relevant information throughout the day you can add our widget to smart stacks. Smart Stacks are a collection of widgets that will automatically rotate to show the right widget at the top. So You can see the most important details at exactly the right time. But you can also swipe through. 
 

 You configure the widget with a timeline provider,  The timeline provider tells WidgetKit when to update your widget’s content.

 [image] (image://docs-assets.developer.apple.com/published/a3427848523d8674136d588fcfbf4954/12000/WidgetKit-Architecture@2x.png)

 And you can add configuration and intelligence to Your widgets. 
 To make a widget user-configurable, you add a custom SiriKit intent definition to your extension. WidgetKit automatically provides a customization interface to let users personalize their widgets.



### What widget can do.

Widget can show main app pivotal content in home screen that user can not open app.

### What is widget featrue.

Because of widget show in iOS home screen, if not limlit widget. The will cast lost battery and user may pay more attion in it. So apple limlit widget. The widget extension is not continually active, even if the widget is onscreen. The widget data reload most be more than 5 minutes. and not available any animations. Widgets present read-only information and don’t support interactive elements such as scrolling elements or switches.

### What widget can do for our app.

We can show all the device info (name, icon, featrue etc) that had connected. After add or remove device in app. Our developer can send the devices data to widget  [WidgetCent]. And can not reload data evert. But the battery not need to show. becaust widget can not to establish connection with the device. 
