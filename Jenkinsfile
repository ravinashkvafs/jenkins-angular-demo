pipeline {
  agent any
  tools { nodejs "node" }
  stages {
    stage('Install') {
      steps { sh 'npm install' }
    }
    stage('Linting') {
      steps { sh 'npm run lint' }
    }
    stage('Build') {
      steps { sh 'npm run build' }
    }
  }
}