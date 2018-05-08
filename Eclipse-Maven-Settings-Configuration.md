Note: If you haven't done so already, you need to install Maven 3.3.9 from the Appstore.

Eclipse comes standard with an embedded version of Maven, but it's the wrong version for us because it lacks the configuration necessary to access the UHG Artifactory repository.  Follow these instructions to configure eclipse to use the Appstore-installed Maven 3.3.9 version:
<P>
<B>Select Window->Preferences:</B><br/>
<P>
[[images/eclipse/window_preferences.jpg|alt=Select Window->Preferences]]
<P>
<B>Under Maven->Installations you will see something like this, click Add:</B><br/>
[[images/eclipse/maven_installations_default.jpg|alt=Click Add]]
<P>
<B>Click Directory, select the Maven 3.3.9 install directory:</B><br/>
[[images/eclipse/maven_installations_select.jpg|alt=Click Directory, select the Maven 3.3.9 install directory]]
<P>
<B>Update the Installation Name field and click Finish:</B><br/>
[[images/eclipse/maven_installations_finish.jpg|alt=Update the Installation Name field and click Finish]]
<P>
<B>Make sure the checkbox for maven 3.3.9 is selected and click Apply and Close:</B><br/>
[[images/eclipse/maven_installations_apply_and_finish.jpg|alt=Make sure the checkbox for maven 3.3.9 is selected and click Apply and Close]]
<P>
<B>Now we need to set the correct maven global settings.xml file configuration. Under Maven->User Settings you will see something like this, click Browse:</B><br/>
[[images/eclipse/maven_settings_browse.jpg|alt=Under Maven->User Settings click Browse]]
<P>
<B>Browse to the Maven 3.3.9 conf directory and select the settings.xml file there:</B><br/>
[[images/eclipse/maven_settings_select.jpg|alt=Browse to the Maven 3.3.9 conf directory and select the settings.xml file there]]
<P>
<B>Click Apply and Close:</B><br/>
[[images/eclipse/maven_settings_apply.jpg|alt=Click Apply and Close]]





