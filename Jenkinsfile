pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''curl -X POST \\
https://testing.sweagle.com//api/v1/tenant/metadata-parser/parse -H "Authorization: bearer 783d4f5b-c260-4cce-936e-00d2483875ab" -d "mds=Client-PRD&parser=all&args=&format=JSON" -o output.json'''
      }
    }

  }
}