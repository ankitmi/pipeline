node {
  withCredentials([string(credentialsId: 'test', variable: 'mysecret')]) {
        echo "${mysecret}"
        def var = "value"
        checkout scm
        sh 'bash test.sh'
  }
}
