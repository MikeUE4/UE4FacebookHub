# UE4SocialHub

Change the $YourPackageName in .uml file to your PackageName.R for exmaple if your package name is com.sample.project then replace $YourPackageName with com.sample.project.R 


![wjskhf](https://user-images.githubusercontent.com/37648290/137561836-a87dafc5-2db1-42bf-aef9-1526012afa71.png)



Get User Details of facebook account by seeking permssion from htttps://facebook.developers.com
and target your user more better.


Register to facebook dvelopers and create your app and get credentails from it.
For more details visit
https://rearandroid.com
<string name="facebook_app_id">{YOUR_FACEBOOK_APP_ID}</string>
<string name="fb_login_protocol_scheme">{YOUR_FACEBOOK_TOKEN}</string>

![newm](https://user-images.githubusercontent.com/37648290/137561901-3a8685ac-700a-4075-9c3c-69a773cf15a5.png)



STEPS:
1. Register at https://developers.facebook.com/
2. Create and App depending upon your usage you may select Game or App
(if you select App you will not get features such as changing username and avataar while login,Invite FRiends and more)
3. After creating your app select setup for login
4. Add your Package name in the Required Project field
5. Add your Packagename.MainActivity in the Required Project class for login function call in the setup section(for example if your package name is com.x.y fill in the filed with com.x.y.MainActivity)
6. Then create a Sha256 using cmd as mentioned in teh setup documentation.
7.now you are able to use Login,Invite friends and Share InGame posts
