pipeline {
agent any
stages {
parallel first branch {
stage ('one') {
git url : 'https://github.com/gouthamanni/Jenkins_pipeline.git,branch :master'
}
}
}
stages {
parallel second branch {
stage ('two') {
git url : 'https://github.com/gouthamanni/examples-java-maven.git,branch:master'
}
}
}
}

