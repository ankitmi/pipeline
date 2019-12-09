node {
  withCredentials([string(credentialsId: 'test', variable: 'mysecret')]) {
        echo "${mysecret}"
        checkout scm
        sh 'bash test.sh'
  }
}
