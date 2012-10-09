===============================================================================
ANDROID MAVEN PLUGIN
===============================================================================

The project home page is at http://code.google.com/p/maven-android-plugin

All documentation is there.

Fix for issue: http://code.google.com/p/maven-android-plugin/issues/detail?id=313

Additional arguments for aapt works with all phrases.

Fix for issue: http://code.google.com/p/maven-android-plugin/issues/detail?id=172

<test>
 ...
 <dontFail>true</dontFail>
 ...
</test> 

Build: mvn clean install -Dmaven.test.skip=true

