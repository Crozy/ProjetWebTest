pipeline{
agent any
stages{
stage('Sonar'){
            steps {
               bat 'mvn sonar:sonar'
            }
         }

stage('Build') {
steps{
	bat 'mvn -B -DskipTests clean package'
	}
   }
}
}