pipeline{
    agent any
        stages{
        stage("1"){
            steps{
                withMaven(
                    maven:'maven',
                    globalMavenSettingsConfig: "5bf3f2d2-ce9d-4ab4-8f28-70294d3fd0b7",
                    mavenSettingsConfig: 'settings'
                ){
                    sh "mvn clean verify"
                }
                echo "Testing 123 but for what"
            }
        }
    }
}