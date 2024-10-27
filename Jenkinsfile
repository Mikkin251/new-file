pipeline {
  agent any
  stages {
    stage('Blood bath')
    {
    steps{
     sh 'git clone https://github.com/Mikkin251/new-file.git'

     sh 'git add .'
}
}
	stage('second stage')
	{
	steps
	{
	sh 'git commit -m "first push" '
}
}
	 stage('second stage')
        {
        steps
        {
        sh 'git push -u origin master'
}
}
}
}



