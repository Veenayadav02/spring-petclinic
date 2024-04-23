pipeline{
    agent any
    
    stages{
        stage('SCM'){
            steps{
                git branch: 'main',
                url: 'https://github.com/Veenayadav02/spring-petclinic.git'
            }
        }
        stage('Maven build'){
            steps{
                sh "mvn clean package"
            }
        }
    }
}
