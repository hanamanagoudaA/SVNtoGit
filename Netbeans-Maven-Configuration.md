Note: If you haven't done so already, you need to install Maven 3.3.9 from the Appstore.

NetBeans comes standard with an embedded version of Maven, but it's the wrong version for us because it lacks the configuration necessary to access the UHG Artifactory repository.  Follow these instructions to configure NetBeans to use the Appstore-installed Maven 3.3.9 version:
<P>
<B>Select Tools->Options:</B><br/>
<P>
[[images/netbeans/tools_options.jpg|alt=Select Tools->Options]]
<P>
<B>Under Java, Select the Maven Tab and the Execution Category:</B><br/>
<P>
[[images/netbeans/maven_select_dropdown.jpg|alt=Under Java, Select the Maven Tab and the Execution Category]]
<P>
<B>Change the Maven Home setting to match the appstore-installed maven directory, and click OK:</B><br/>
<P>
[[images/netbeans/maven_set_339.jpg|alt=Under Java, Select the Maven Tab and the Execution Category]]


