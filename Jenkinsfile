pipeline {
    agent any
    stages {
        stage ('Compile Stage') {

            steps {
                    maven : 'maven_3_6_2'
                    bat 'mvn clean compile'
                }
            }
        

        stage ('Testing Stage') {

            steps {
                    maven : 'maven_3_6_2'
                    bat 'mvn test'
                }
            }
    }
}
