pipeline {
    agent any
    parameters {
    choice choices: ['prod', 'dev', 'sit', 'pt'], description: 'select an one environment', name: 'env'
    }
    environment {
    JAVA_VERSION = "11.0.8"
    }
    stages {
        stage('working with git clone'){
            steps{
                script{
                    println "Hii team im groovy scripting"
                    // working with parameters
                    println "my parameter value is ${params.env}"
                    // working with environment variables
                    println "my environment variable value is ${env.JAVA_VERSION}"
                    sh "java -version"
                }
            }
        }
    }
}
