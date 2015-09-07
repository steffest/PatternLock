# PatternLock
Standalone javascript library to transform a standard password input box of a HTML form into a 9-dot pattern lock.
Targeted at mobile webapplications where drawing a pattern on the touchscreen is far easier than typing in a password.

Works on every major desktop and mobile browser.

<img src="http://blog.stef.be/5/Steffest_API_Javascriptlibrary9dotPatternLock_AA9C_patternlock_example_3.jpg">

(This repository was moved from https://9dotpatternlock.codeplex.com/)

Example use  
Copy the _img,_script and _style folders to your hosting  
Copy these 2 lines in your HTML source  

&lt;link rel="stylesheet" type="text/css" href="_style/patternlock.css"/>  
&lt;script src="_script/patternlock.js">&lt;/script>  

give your password input element the className "patternlock"  
e.g. &lt;input type="password" name="password" class="patternlock">

Live demo at http://www.stef.be/dev/javascript/patternlock/
