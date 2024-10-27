pipeline
{
agent any
stages
{
stage('maven clean')
{
steps
{
sh "mvn clean"
}
}
stage('maven validate')
{
steps
{
sh "mvn validate"
}
}
stage('maven compile')
{
steps
{
sh "mvn compile"
}
}
stage('maven test compile')
{
steps
{
sh "mvn test compile"
}
}
stage('test')
{
steps
{
sh "mvn test"
}
}
stage('package')
{
steps
{
sh "mvn package"
}
}
stage('maven install')
{
steps
{
sh "mvn install"
}
}
}
}


