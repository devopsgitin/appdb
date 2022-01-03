pipeline{
    agent{
        label 'agent1'
    }
    tools{
        maven 'mvn384'
    }
    stages{
        stage("Maven Build"){
            steps{
                sh 'mvn clean package'
            }
        }
    }
}