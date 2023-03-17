pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/demo-syte/Ansible-Automate-Project', branch: 'Ansible-Automate-Project', changelog: true, poll: true)
      }
    }

    stage('print message') {
      steps {
        echo 'Bild working!'
      }
    }

  }
}