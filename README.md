Here's a simple Jenkins pipeline script that echoes "Hello World":

```
pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}
```

Let me explain what each part does:

- `pipeline { ... }`: Defines the pipeline.
- `agent any`: Specifies that the pipeline can run on any available agent.
- `stages { ... }`: Defines the stages of the pipeline.
- `stage('Hello World') { ... }`: Defines a stage named "Hello World".
- `steps { ... }`: Defines the steps within the stage.
- `echo 'Hello World!'`: Prints "Hello World!" to the console.

To use this script in Jenkins:

1. Create a new Jenkins job.
2. Choose "Pipeline" as the job type.# hack