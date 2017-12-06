#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/ManojPeddireddy/MultibranchPipeline.git/'],
    pipelineTriggers([githubPush()])])


pipeline {
    agent any

    stages {
        
        stage('Build') {
            steps {
                sh 'git branch'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Hello World"'
            }
        }
    }
}
