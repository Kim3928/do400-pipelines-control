pipeline {
 agent {

   node {
     label 'nodejs'
     }
   }
   stages {
   stage('Backend Tess') {

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
