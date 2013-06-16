# Gradle Google play services library project
***

**Gradle compatible** google play services library project.  
Google play services version : 3.1.36 (673201-10)


### Configuration

1. Copy past the `googleplayservices-gradle` folder into your project. Do it within a file explorer, not within Android Studio because some files will be ignored.

2. Edit `settings.gradle` from your project and add : `:googleplayservices-gradle` or `:libraries:googleplayservices-gradle` if you respect the standard structure.

3. Edit `build.gradle` from your project's main module and add : `compile project(':libraries:googleplayservices-gradle')`


You may need to regenerate the gradle's projects structure (gradle tab in AS or close/reopen the project).