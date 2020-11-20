pipeline{
        agent any
        stages{
            stage('build'){
              steps{
              bat 'mvn -f C:/Users/Chauch/.jenkins/workspace/nexus-maven/my-app install'
             }
            }
            
            stage('test'){
              steps{
              echo 'Test Stage'
             }
            }
            stage('deploy'){
              steps{
              bat 'mvn -f C:/Users/Chauch/.jenkins/workspace/nexus-maven/my-app deploy'
             }
            }
        }
}
