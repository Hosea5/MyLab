pipeline {
    // Derectives
    agent any
    tools {
        maven 'maven'
    }


    stages
    // Specify various stage within stages 
    stage ('build') {
        steps {
            sh 'maven clean install package'
        }
    }

  // Stage2: Testing 
    stage ('Test') {
        steps {
            echo 'testing....'
        }
    } 

    // Stage3: Deploying
    stage ('Deploy') {
        steps {
            echo 'deploying....'
        }
    } 
 
}