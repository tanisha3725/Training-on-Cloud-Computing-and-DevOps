# 📘 DAY 4

## Jenkins Pipeline and Jenkinsfile

Today, we explored how Jenkins Pipelines define and automate a sequence of software delivery stages. We learned about Jenkinsfiles and 
the basics of Groovy syntax used in pipeline scripts.

## What Is a Jenkinsfile?

A Jenkinsfile is a text file that defines a Jenkins Pipeline as code. It is commonly stored in the root directory of a project's 
repository so that the pipeline definition can be version-controlled with the application.

## Basic Pipeline Structure

A Declarative Pipeline typically contains:

- **pipeline:** Defines the pipeline.
- **agent:** Specifies where the pipeline or its stages can run.
- **stages:** Groups the main stages of the workflow.
- **stage:** Defines an individual stage.
- **steps:** Contains the actions executed within a stage.

## Example Jenkinsfile

```groovy
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }
    }
}
```

This is a simple illustrative example. It prints messages rather than building or testing a real application.

## Introduction to Groovy

Groovy is a programming language used to write Jenkins Pipeline scripts. It supports variables, expressions, and control structures that 
can help define automation logic.

## Key Learnings

- Understood the purpose of a Jenkinsfile.
- Learned the basic structure of a Declarative Pipeline.
- Explored the roles of stages and steps.
- Learned how pipeline code can be stored in a project repository.
- Gained an introduction to Groovy syntax.

## Conclusion

This session explained how pipelines can be defined as code, making automation workflows easier to maintain, review, and manage 
alongside application source code.
