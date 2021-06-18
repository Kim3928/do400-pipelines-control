pipeline {
 agent {

   node {
     label 'nodejs'
     }
   }
   stages {
   stage('Backend Test1') {

    steps {

        sh 'node ./backend/test.js'

        }

    }  

    stage('Frontend Tests') {

    steps {


    sh 'node ./frontend/test.js'

    }
    }
    }
}
