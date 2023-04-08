pipeline {
    agent any
    stages {
        stage('working with conditions'){
            steps{
                script{
                    myvalue = input message: '', parameters: [string(name: 'myvalue', trim: true)]
                    if (myvalue.toInteger() == 20) {
                        println "value is correct"
                    }
                    else{
                        println "value is in-correct"
                    }
                }
            }
        }
    }
}
