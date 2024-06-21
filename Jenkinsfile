pipeline {
          agent any
          stages {
              stage('Build') {
                  steps {
                      script {
                          // Choisissez la commande en fonction de votre script
                             
			     bat 'python3 hello.py' // Pour Python

                          // bat 'javac HelloWorld.java && java HelloWorld' // Pour Java
                      }
                  }
              }
          }
      }
