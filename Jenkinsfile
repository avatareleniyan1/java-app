@Library('my-shared-library1') _

pipeline{

    agent any

    stages{

        stage('Git Checkout'){

            steps{

                gitCheckout(
                branch: "main",
                url: "https://github.com/avatareleniyan1/java-app.git"
            )                     
                
            }
        }
    }
}