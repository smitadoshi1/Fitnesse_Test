pipeline {
  agent any
  stages {
    stage('Build WOW') {
      steps {
        sleep 5
      }
    }
    stage('Fitnesse-Functional-Allocation Suite') {
      parallel {
        stage('Fitnesse-Functional-Allocation Suite') {
          steps {
            echo 'Testing Allocation Test'
          }
        }
        stage('Fitnesse-Functional-Counting-Suite') {
          steps {
            echo 'performing counting test'
          }
        }
        stage('Fitnesse-Intelligent-Fullfillment-Suite') {
          steps {
            echo 'Testing Intelligent Suite'
          }
        }
        stage('Fitnesse-functional-Inventory-Suite') {
          steps {
            echo 'Print inventory suite'
          }
        }
        stage('Fitnesse-Functional-OrderProcessing-Suite') {
          steps {
            echo 'Testing 1 2 3'
          }
        }
        stage('Fitnesse-Parcel-Suite') {
          steps {
            echo 'finished testing'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        sleep 4
      }
    }
  }
}