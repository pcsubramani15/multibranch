node('built-in') 
{
    stage('Continuous Download_built') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_built') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
