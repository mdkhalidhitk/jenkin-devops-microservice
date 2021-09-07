
pipeline {
agent {
    docker {
        image 'maven:3.8.1-adoptopenjdk-11'
        label 'myMaveen'
        args  '-v /tmp:/tmp'
    }
}
}