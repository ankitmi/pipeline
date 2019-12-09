node {
  withCredentials([string(credentialsId: 'test', variable: 'mysecret')]) {
        echo "${mysecret}"
        sh test.sh
  }
}
