pipeline {
  agent any
  stages {
    stage('Example Build') {
      steps {
        def MyClass = load "src/MyClass.groovy"
        print "Result " + MyClass.testMethod()
      }
    }
  }
}
