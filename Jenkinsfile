pipeline {

      agent { 
            node { 
                  label 'master' 
                  customWorkspace '/home/mangesh/Software/Work'
            }
      }
      
      stages {
         stage('Dev1') {
            steps {
               echo "Hello dev 1"
            }
         }
         stage('Dev2') {
            steps {
               echo "Hello dev 2"
            }
         }
         stage('Dev3') {
            steps {
               echo "Hello dev 3"
            }
         }
         stage('Dev4') {
            steps {
               echo "Hello dev 4"
            }
         }
      }

}
