Follow these instructions to configure a Tomcat 7 instance to run in eclipse:
<P>
<B>Select Window->Preferences:</B><br/>
<P>
[[images/eclipse/window_preferences.jpg|alt=Select Window->Preferences]]
<P>
<B>Under Server->Runtime Environments you will see something like this, click Add:</B><br/>
[[images/eclipse/tomcat_runtime_add.jpg|alt=Click Add]]
<P>
<B>Select Apache Tomcat v7.0 and click Next:</B><br/>
[[images/eclipse/tomcat_select_v7.jpg|alt=Select Apache Tomcat v7.0 and click Next]]
<P>
<B>Select Browse and select your Tomcat installation home:</B><br/>
[[images/eclipse/tomcat_browse.jpg|alt=Select Browse and select your Tomcat installation home]]
<P>
<B>Select the JDK7 JRE and click Finish:</B><br/>
[[images/eclipse/tomcat_select_jre_dropdown.jpg|alt=Select the JDK7 JRE and click Finish]]
[[images/eclipse/tomcat_select_jre_7.jpg|alt=Select the JDK7 JRE and click Finish]]
<P>
<B>Click Apply and Close:</B><br/>
[[images/eclipse/tomcat_apply_and_close.jpg|alt=Select the JDK7 JRE and click Finish]]
<P>
<P>
The default timeout for deploying a war to Tomcat in eclipse is 45 seconds, which is too short for our war. We should change it to a less stringent 120 seconds:
<P>
<B>Open the Server Window and double-click the Tomcat server which we just added above:</B><br/>
[[images/eclipse/tomcat_server_select_properties.jpg|alt=Open the Server Window and double-click the Tomcat server which we just added above]]
<P>
<B>After double clicking the server you should see a settings window. Expand the Timeouts section and change the start timeout to 120:</B><br/>
[[images/eclipse/tomcat_server_set_timeout.jpg|alt=After double clicking the server you should see a settings window. Expand the Timeouts section and change the start timeout to 120]]
<P>
<B>Click the x in the tab to close the settings window, and click Save:</B><br/>
[[images/eclipse/tomcat_server_timeout_save.jpg|alt=Click the x in the tab to close the settings window, and click Save]]
<P>



