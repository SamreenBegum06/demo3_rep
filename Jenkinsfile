pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/SamreenBegum06/demo3_rep.git'
}
}
stage("build")
{
steps{
sh 'javac hello.java'
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
}
