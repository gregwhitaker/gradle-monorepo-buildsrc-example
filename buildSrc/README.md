# buildSrc

Shared Gradle buildSrc directory where you could hold tasks and plugins that are used in projects across the monorepo.

## Adding Shared buildSrc to Project
In the project's `build.gradle` file you will need to add a reference to the `buildSrc` project in the 
buildscripts closure:

    buildscript {
        repositories {
            mavenCentral()
        }
    
        dependencies {
            classpath 'example.gcb.gregwhitaker:buildSrc'
        }
    }