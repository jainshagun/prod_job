pipeline {
    agent any
    stages {
        stage('JIRA') {
            // Look at IssueInput class for more information.
            def testIssue = [fields: [ // id or key must present for project.
                               project: [key: 'GAR'],
                               summary: 'New JIRA Created from Jenkins.',
                               description: 'New JIRA Created from Jenkins.',
                               // id or name must present for issueType.
                               issuetype: [name: 'Change']]]

            response = jiraNewIssue issue: testIssue
            echo response.successful.toString()
            echo response.data.toString()
        }
    }
}
