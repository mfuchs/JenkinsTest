pipeline {
    agent any

    paramters {
        string(name: 'NAME', defaultValue: 'John Doe', description: 'Your name')
    }

    stages {
        stage("Stage 1") {
            steps {
                echo "Hello ${params.NAME} from stage 1"
            }
        }

        stage("Stage 2") {
            steps {
                echo "Hello ${params.NAME} from stage 2"
            }
        }
    }
}
