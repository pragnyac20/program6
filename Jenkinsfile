pipeline{
      agent any 
        tools{
              maven 'maven_home'
           }
        stages{
              stage('BUILD'){
                         steps{
                               bat 'mvn clean install'
                          }
}
}
}