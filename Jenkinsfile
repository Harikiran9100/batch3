pipeline {
    agent any
    parameters {
    choice choices: ['prod', 'dev', 'sit', 'pt'], description: 'select an one environment', name: 'env'
    }
    stages {
        stage('working with git clone'){
            steps{
                script{
                    println "Hii team im groovy scripting"
                }
            }
        }
    }
}
