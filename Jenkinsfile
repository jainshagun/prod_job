node {
  stage('JIRA') {
    def issue = jiraGetIssue idOrKey: 'GAR-21'
    echo issue.data.toString()
  }
}
