# MarQueeTextView
 **带跑马灯效果的TextView** 由于项目中需要用到跑马灯效果，然后安卓系统自带的跑马灯效果在**失去焦点**后会停止滚动。所以自己看了看textView源码，
 自定义了textView并重写了isFocused、onWindowFocusChanged、onFocusChanged这几个回调方法。 从而完成了永不停止滚动的TextView，不过现在还有个bug，当你
 在listView中使用此TextView时会有导致Item不可点击的问题。目前我没有时间解决。
  