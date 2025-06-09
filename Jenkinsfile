pipeline{
  agent any
  tools{
    maven "Maven_Home"
  }
  stages{
    stage("Build")
    {
      steps{
       dir('p6') {
            bat 'mvn clean install'
        }}
  }}
}
