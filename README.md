Webview URL’s for UPI Intent


Android:- Generic in android

upi://pay?pa=TexterityPrivateLimi.payu@mairtel&pn=Texterity%20Private%20Limited&tr=20253392480&tid=PPPL20253392480270624203021&am=1.00&cu=INR&tn=UPIIntent 


IOS:- App specific in iOS

gpay://upi/pay?pa=payumoney@hdfcbank&pn=varun%20vohra&tr=20282875973&tid=PPPL20282875973010724114025&am=1.00&cu=INR&tn=UPIIntent



specific intent:-

intent://pay?pa=oyorooms.payu@hdfcbank&pn=NIMIT%20BHATIA&tr=20283018805&tid=PPPL20283018805010724115619&am=10.00&cu=INR&tn=UPIIntent#Intent;scheme=upi;package=com.google.android.apps.nbu.paisa.user;S.browser_fallback_url=https%3A%2F%2Fapi.payu.in%2Fpublic%2F%23%2F8389d34bc914f4b638f22f6816d09ccb%2FupiLoader%3FcancelAndRetry%3Dtrue%26app%3Dgooglepay;end
 


KT part

webviewSpecificIntent :- This flag Mandatory for specific intent handling [condition:- nonsealess>>webview>>specific intent] [This flag is only for Android specific intent not for ios] [javascript enable must be "true" at merchant end] 

Package name must be added inside the manifest file

How to search package name:-
playstore>> search app>>  ?id=xyz (in browser url appened in last is package name) e.g id= money.jupiter&hl=en_IN

iOS - Generic Intent not support only support specific intent

In Webview surl/furl redirection not happening


Testing web view by using below link:-


https://756zx792-5500.inc1.devtunnels.ms/upi_Intent_Testing.html


UPI Mandate URI string  upi://mandate?pa=kk.payutest@hdfcbank&pn=&mn=UPISubscription&tid=PPPL403993715533570625200325122855&validitystart=20032025&validityend=14012028&am=5500.00&fam=5500.00&amrule=MAX&recur=MONTHLY&recurvalue=20&recurtype=AFTER&tr=403993715533570625&cu=INR&mc=4816&tn=UPIIntent&mode=13&purpose=14&orgid=159240&rev=&block=N&txnType=CREATE
