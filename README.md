# TopActivity
###展示当前app所处的最顶activity<br>
####GIF展示：<br>
![](https://github.com/FantasyEngineer/TopActivity/blob/master/topdemo.gif)  <br>
###引入：<br>
Step 1.Add it in your root build.gradle at the end of repositories:<br>
	allprojects {<br>
		repositories {<br>
			...<br>
			maven { url 'https://jitpack.io' }<br>
		}<br>
	}<br> 
  <br>
  Step 2. Add the dependency <br>
 	dependencies {<br>
	        compile 'com.github.FantasyEngineer:TopActivity:V1.0'<br>
	}<br>

###代码使用<br>
```Java
     //展示
TaskWindowManage.INSTANCE.ShowInApplication(MainActivity.this);
      //消失
TaskWindowManage.INSTANCE.dismiss(MainActivity.this);
```



