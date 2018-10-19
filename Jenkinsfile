pipeline {

  agent { 
  label 'Linux' 
  } 
  stages { 
  stage ('Script') { 
    steps { 
      sh 'chmod +x ilki.sh'
      sh './ilki.sh' 
      } 
  } 
} 
}
