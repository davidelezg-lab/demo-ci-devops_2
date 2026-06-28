pipeline {
    agent any

    stages {
        //  Hemos borrado el stage "Clonar código" porque Jenkins ya lo hace solo

        stage('Instalar dependencias') {
            steps {
                // Aquí tus comandos, por ejemplo en Windows:
                bat 'npm install' 
            }
        }
	stage('Test') {
    	    steps {
        	bat 'npm test'
    }
}
        stage('Ejecutar app (test simple)') {
            steps {
                bat 'npm test'
            }
        }
    }
}