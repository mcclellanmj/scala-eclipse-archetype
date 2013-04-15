Scala / Java Eclipse Maven Archetype
====================================
This is a Maven archetype to create a standard layout scala - java project.  It does not create any boilerplate code it, it simply creates the bare necessities for a scala/java project that can import to Eclipse.  And yes test frameworks are essential :) 

To install this archetype use the command 

	mvn clean install

Once installed you can generate by typing

	mvn archetype:generate -DarchetypeGroupId=com.mcclellan -DarchetypeArtifactId=scala-eclipse-archetype -DarchetypeVersion=0.3.1-SNAPSHOT

This will create a new directory with the artifactId given by you as the name, it will have standard maven directory layout in it.
You can generate all your Eclipse metadata so that it can be imported by using the command from inside your newly created project

	mvn eclipse:eclipse
