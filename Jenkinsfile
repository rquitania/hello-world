pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                echo "This is a PR!"
                echo "This is another change!"
                echo "This is another change!"
                echo "One more change!"
                echo "This is a test"
                echo "Test 2/9 @ 3PM"
                echo "Test 2/9 @ 4:42PM"
                echo "Test 2/10 @ 1:27PM"
                echo "Test 2/11 @ 1:53PM"
                echo "Test 2/11 @ 2:46PM"
                echo "Test 2/11 @ 3:00PM"
            }
        }
        /*
        stage('update jira') {
              try {
                    error "Exception"
                } catch(error) {
                    def comment = "${BUILD_URL} FAILED - ${ERROR}"
                    jiraAddComment idOrKey: 'GENERIC-999', comment: comment, site: 'YOURJIRASITE'
                    currentBuild.result = 'FAILURE'
                }
        }
        */
    }
}
