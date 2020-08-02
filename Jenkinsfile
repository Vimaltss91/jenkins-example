pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            tool name: 'MAVEN_HOME', type: 'maven'

            steps {
                    sh 'mvn clean compile'
            }
        }
    }
}
