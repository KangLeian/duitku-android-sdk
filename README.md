<h1>duitku-sdk-android</h1>


<b>Welcome to,</b> Duitku Android SDK registration page, Integrate this SDK to start transaction using duitku in your android application.


<h2>Installations</h2>

<h3>Server Merchant</h3>


```html
	Base Url 		: https://merchant.com/api/
	Request Transaction 	: https://merchant.com/api/requestTransaction.php
	Check Transaction	: https://merchant.com/api/checkTransaction.php
	List Payment		: https://merchant.com/api/listPayment.php
```
Download sample file <a href="https://github.com/duitkupg/duitku-android-sdk/blob/master/Webserver/requestTransaction.php" download="requestTransaction.php">requestTransaction.php</a>&nbsp;&nbsp;<a href="https://github.com/duitkupg/duitku-android-sdk/blob/master/Webserver/checkTransaction.php" download="checkTransaction.php">checkTransaction.php</a>&nbsp;&nbsp;<a href="https://github.com/duitkupg/duitku-android-sdk/blob/master/Webserver/listPayment.php" download="listPayment.php">listPayment.php</a>


<h3>Recommended specifications for your application development</h3>


```html
	Development Tool       		 : Android Studio 3.4 > 
	Gradle Version         		 : 3.4.1 > 
	Target SDK Version     		 : API Level 29 
	Minimum SDK Version   		 : API Level 21 (Lollipop) 
```





How to try example
Visit and try the app module to see an example of how the SDK works.



<h3>Installation</h3>

<h4>Maven</h4>

```html
	<repositories> 
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

```html
	<dependency>
	    <groupId>com.github.duitkupg</groupId>
	    <artifactId>DuitkuSDK</artifactId>
	    <version>1.0</version>
	</dependency>
```

For more information, visit https://bintray.com/duitku/android/duitku-sdk-android

<h4>Build.gradle(Module:app)</h4>

```html
	implementation 'com.duitku:sdk-android:1.0'
```

<h4>Build.gradle</h4>

```html
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```


link ..



<h3>Full step Installation </h3>
Download  <a href="https://github.com/duitkupg/duitku-android-sdk/blob/master/Docs/requestTransaction.php" download="requestTransaction.php">Duitku-Android-sdk-docs.pdf</a>

