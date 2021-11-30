pipeline { 

  agent any 

  stages { 

    stage('Build'){ 

      steps { 

        echo 'Building application'
        bat 'npm install'
        bat 'npm start'

      } 

    } 

    stage('Deploy') { 

      steps {  

        echo 'Deploying application'  

      } 

    } 

  } 

} 
