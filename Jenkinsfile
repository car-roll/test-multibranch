pipeline {
  agent any
  options { overrideIndexTriggers(env.CHANGE_ID == null) }
  stages {
     stage('Hello') {
        steps {echo "i am overriding"}
     }
  }
}
