mudroid-workshop-2
==================
Created by Matthew Browne for Mudroid, the Monash University Android Community.
Last edited 05/05/2012.


###PROJECT:		LocationAware from the Android Developers site http://developer.android.com/training/basics/location/index.html								
###AIM: 		Discuss App idea's and how to start writing an Android App from a concept alone. Investigate reverse geocoding through the sample App code.
###COMPATIBLE Android versions: 2.1 to 4.0.3 (which is sdk version 7 to 15)
##Discussing App Ideas
###Requirements for an Android App
- Cool
- Simple
- Polished
- Fun
- Novel

###App Idea's
- Location Aware
	- Uni library/Shop discount notifications
- Social Networking
- News/RSS Feed
- IM 
	- Jabber
	- Native university messaging app with push messages for offline
- Games
	- 3D out of our realm, maybe OpenGL?
	- 2D games 
		- Lots of card games and older games not done yet
- Admin Tools for Schools, Unis, Businesses, etc.
	- Like Moodle
	- Staff difference to Student
	- Subject/Faculty
	- IT admin-ware, SSH, Tunnelling
- Engineering Tools (for solving problems in maths, physics, electronics, etc.)
- ID cards Barcode saver/store so we don't have to pull out our cards all the time
- Mobile display of interesting datasets e.g. http://data.gov.au/
	- Crime Heat Map
	- National Public Toilet Map

###Considerations:
- Offline (client-side) or on-line (server-side) big database
- Do something new, or do something already done but do it better?

##Starting to write an Android App with an App concept
* Search in the Google Play Store for other Applications that are similar to our idea https://play.google.com/store?hl=en
* What ideas can we get from them? Are any open source?

If they are open sourced, download the source code from the repository and import it into Eclipse IDE to have a play with.
*Remember that OSS Licences are attributable to derivatives of the original source code.*

* Find sample's that relate to our idea from the Android SDK Samples http://developer.android.com/resources/browser.html?tag=sample
	- For an NFC Contacts Swapping App, we found SDK/android-sdk-macosx/samples/android-15/NFCDemo and SDK/android-sdk-macosx/samples/android-15/ContactManager

* Open the Sample Apps in Eclipse IDE:
	- Open Eclipse IDE and create a workspace
	- File -> New -> Android Project
	- Select "Create project from existing source" and click Next
	- Choose a build target, you should go as high as possible = Android 4.0.3 and click Next
	- From the list of samples, choose the relevant project to create, click Finish
	- Repeat these steps for every sample project that relates to the App idea

* Build, run and play with the source code. Modify sections to see what the changes do.

When you feel ready, create a new android project and copy sections from the sample source to create a protoype.

##Handy references for implementing a new App
- This http://developer.android.com/resources/index.html is the best place to start.
- The left pane contains most of the topics needed to start building an Android App.
- Tutorials are also a great way to get a feel for what you'll need to do http://developer.android.com/resources/browser.html?tag=tutorial
- Choose and follow a tutorial that closely relates to your idea.
- Topics can be found here too http://developer.android.com/resources/topics.html
- You'll need to decide on an appropriate layout for your interface.
- Select the most appropriate View for your app http://developer.android.com/resources/tutorials/views/index.html
- The Activity lifecycle is probably the most important process of an Android App.
- Get to know it well, get to love it. http://developer.android.com/reference/android/app/Activity.html

Once again, bookmark the Resources tab on the Android Developer site, the left pane contains most of the resources necessary to build an Android App.
