node {
  withCredentials([string(credentialsId: 'test', variable: 'mysecret')]) {
        echo "${mysecret}"
        checkout scm
        sh 'test.sh'
  }
}
