TEIID Translator Arche Type
================

This maven project is use to create the TEIID Translator archetype, which then can be used to generate a new translator project.

When the translator project is generated, you will end up with the following structure:

-  translator-typename
	|-	kits
		|-	wildfly
			|-	docs
				|-	teiid-extensions
					|-	datasources
						|-	typename	
							|-	add-translator-typename.cli
			|-	modules
				|-	.jar
					|-	main
						|-	module.xml
		|-	wildfly-dist.xml 
	| -	pom.xml
	| -	src
		|-	main
			|-	java
				|-	.jar
					|-	TranslatorNameConnection.java
					|-	TranslatorNameExecution.java
					|-	TranslatorNameExecutionFactory.java
					|-	TranslatorNamePlugin.java
			|-	resources
				|-	.jar
						|-	i18n.properties
				|-	META-INF
					|-	services
						|-	org.teiid.translator.ExecutionFactory

