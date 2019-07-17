node{
    stage("SCM checkout")
    {
       git 'https://github.com/chandrakiran88/website.git'
      }
      stage("Compile-Package")
      {
          def mvnHome = tool name: 'm3', type: 'maven'
          sh "${mvnHome}/bin/mvn package"
      }
      
}
