dipeline{
agent any
stages{
stage('Deploy'){
steps{
echo "test sucessful"
bat"mvn compile"
}
}
stage('Build'){
steps{
echo "build sucessful"
bat"mvn clean"
}
}
stage('Test'){
steps{
echo "test sucessful"
bat"mvn test"
}
}
}
}
