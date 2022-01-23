node {
  try {
    stage('checkout') {
      checkout scm
    }
    stage('prepare') {
      sh "git clean -fdx"
    }
    stage('buikd') {
      echo "buikd..."
    }
    stage('test') {
      echo "test"
    }
    stage('deploy') {
      //sh "tar -cvzf hello.tar.gz hello.sh"
      echo "deploy"
    }
    stage('Delivery') {
      echo "Delivery"
    }
  } finally {
    stage('cleanup') {
      echo "doing some cleanup..."
    }
  }
}echo 
