# Note
三方开源库 ：<br>
BlurKit				模糊<br>
弹簧				faceBook开源空间，rebounds，SpringChain<br>
开源日历			materialcalendarview<br>
向上滑 划出一个新的fragment	SlidingUpPanelLayout	<br><br>
tips：<br>
一<br>
imageview,drawable设置状态，可以用来保持点击状态：<br>
设置状态:setImageState(Android.R.attr.state_focused, true);<br>
取消状态：setImageState(new int[ ] { }, true);<br><br>
二<br>
倒计时 TImeCount，之前一直都是用属性动画。。。。<br><br>
三<br>
使根部局变按，((FrameLayout)(getWindow().getDercorView().findViewById(android.R.id.content))).addView(View view)<br>
加一个带背景的view就可以，需要明白一点activity的视图层次。FrameLayout的特点，设置foreGround只是当前上面一层。<br><br>
