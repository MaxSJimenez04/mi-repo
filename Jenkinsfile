pipeline{
    agent any
    stages{
        stage('Clonar codigo'){
            steps{
                git 'https://github.com/MaxSJimenez04/mi-repo.git'
            }
        }
        stage('Compilar'){
            steps{
                sh 'echo "Compilando el proyecto..."'
            }
        }
        stage('Pruebas'){
            steps{
                sh 'echo "Ejecutando Pruebas..."'
            }
        }
    }
}