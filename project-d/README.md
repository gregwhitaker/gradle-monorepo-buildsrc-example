# project-d

Example project that does not depend on any other projects in the monorepo.

## Building the Project
Run the following command to build the project:

    ./gradlew build
    
## Running the Project
Run the following command to start the application:

    ./gradlew run
    
If successful, you will see the following in the console:

    > Task :run
    This is project-d!
    
## Running the HelloWorldTask from buildSrc
Run the following command to execute the task:

    ./gradlew hello
    
If successful, you will see the following in the console:

    > Task :hello
    Hello from task :hello!