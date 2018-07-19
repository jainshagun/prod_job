pipeline {
    agent any
    stages {
        stage('JIRA') {
            def fields = jiraGetFields idOrKey: 'GAR-3'
            echo fields.data.toString()
        }
    }
}
