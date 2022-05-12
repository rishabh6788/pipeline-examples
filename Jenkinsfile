pipeline {
    agent any 
    stages {
        stage('Pipeline to seed or update all pipelines') {
            steps {
                jobDsl  targets: ['declarative-examples/simple-examples/*.groovy']
            }
        }
    }
}
