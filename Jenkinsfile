pipeline {
    agent any
    environment {
        INSTAGRAM_DFBASTIDAS = "@dfbastidas"
    }
    
    stages {
        stage("Saludo 1"){
            steps {
                echo "Hola desde saludo 1"
            }
        }
        stage("Saludo 2"){
            steps {
                echo "Hola desde saludo 2, paso 1"
                echo "Hola desde saludo 2, paso 2"
            }
        }
        stage("Imprimir variables de entorno"){
            steps {
                echo "${env.INSTAGRAM_DFBASTIDAS}"
                echo "${INSTAGRAM_DFBASTIDAS}"
                echo "INSTAGRAM_DFBASTIDAS"
                echo "=============================="
                sh "echo ${env.INSTAGRAM_DFBASTIDAS} "
                sh "echo ${INSTAGRAM_DFBASTIDAS} "
                sh "echo INSTAGRAM_DFBASTIDAS "
            }
        }
    }
}
