## guava preconditions ##

**Master Build Status:**
[![Circle CI](https://circleci.com/gh/OrdnanceSurvey/guava-preconditions.svg?style=svg)](https://circleci.com/gh/OrdnanceSurvey/guava-preconditions)

This is a tiny subset of the guava project containing only the preconditions (and immediate dependency classes).

## Use it ##

include a gradle reference:

    compile 'uk.co.ordnancesurvey.external:guava-preconditions:0.1.0-SNAPSHOT'

# Maintainer Repo Configuration #
The maintainer should consider adding the following to their properties file:

    ~/.gradle/gradle.properties
       mavenUser=nexusUser
       mavenPassword=nexusPassword

If you are working on a CI environment, such as Circle CI, you can specify gradle environmental variables using the "ORG_GRADLE_PROJECT" prefix:

    export ORG_GRADLE_PROJECT_mavenUser="nexusUser"
    export ORG_GRADLE_PROJECT_mavenPassword="nexusPassword"
