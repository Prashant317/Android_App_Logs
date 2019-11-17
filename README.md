# Android_App_Logs
In this Repository general basic description about how log state works in an Android Application have been explained. Log states like onCreate, onResume, onDestroy, onResume, onStop etc. Whenever user press back button, homebutton. So, accordingly these all logs will save your data or destroy the app sessions, maintain the sessions etc.



# Understand How to write code

Hello,

So as I mentioned this repository will guide you how to work with the application log states.

To do this firstly we need to import a java (Log) library => import android.util.Log;

Now after import make your own string like this  =>  private static final String tag = "Mymessage";

Now inside the main method press alt + insert and choose override methods and select all states and take them into your java code file.

Now inside them write  =>  Ex: -> Log.i(tag,"onCreate"); do the same for all states

Then you are all done now run your application in emulator and come in logcat bottom of your android studio after building and running your application in the emulator.

Now to filter choose edit filter configurate and write its name => Mymessage

Now finally come to the Run at bottom of android studio and operate your application in emulator and see state effects.

Congrats... You are done with this thing.

:)
