pipeline {
    agent any

  tools {
      jdk "jdk17"
      maven  "M3"
  }
  
    stages {
        stage('Git clone') {
            steps {
                echo 'Git clone'
                git url: 'https://github.com/LIMSEOKH/spring-petclinic.git',
                    branch: 'efficient-webjars'
            }
        }
    }
}
