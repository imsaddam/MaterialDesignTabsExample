# MaterialDesignTabsExample

Android Design Support Library made our day easier by providing backward compatibility to number of material design 
components all the way back to Android 2.1. In Design support Library the components like navigation drawer, 
floating action button, snackbar, tabs, floating labels and animation frameworks were introduced.
In this article we are going to learn how to implement material tabs in your apps.


Tabs are now best implemented by leveraging the ViewPager with a custom "tab indicator" on top. 
In this guide, we will be using Google's new TabLayout included in the support design library release for Android "M".

Prior to Android "M", the easiest way to setup tabs with Fragments was to use ActionBar Tabs as described in ActionBar Tabs 
with Fragments guide. However, all methods related to navigation modes in the ActionBar class (such as setNavigationMode(), 
addTab(), selectTab(), etc.) are now deprecated.
