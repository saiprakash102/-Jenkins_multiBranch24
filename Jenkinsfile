node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loans') 
	{
    input 'waiting for tester approval'		
    sh label: '', script: 'mvn package'
	}
}
