## Client-side Facebook Login ##

**Version: 1.0.0**

Date: 2013/4/10

Comment: First Upload.


##Description##

This is the client-side login of Facebook using jssdk.

You should set the following variable to let it work.

1) In head tag

	<meta property="fb:admins" content="YOUR_ADMIN_ID"/>
  	<meta property="fb:app_id" content="YOUR_APP_ID"/>

2) and in javascript

	FB.init({
		...
		appId      : 'YOUR_APP_ID', // App ID
	    channelUrl : 'YOUR_URL', 
		...
	});

	...

	FB.ui({
		...
		link: 'YOUR_URL'
		...
	});

##Reference##

1. [[Tutorial] Step by step – Implement Facebook Mobile Web In 5 Steps](http://androchen.qov.tw/wordpress/2012/11/08/facebook-mobile-web-step-by-step/)
2. [Facebook Mobile Web Tutorial](https://developers.facebook.com/docs/guides/mobile/web/)