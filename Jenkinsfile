pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'mvn -DskiptTests clean package'
            }
        }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    }
}
