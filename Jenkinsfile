node {
  stage('JIRA') {
    withEnv(['JIRA_SITE=https://jira.sainsburysargos.io']) {
      def issue = jiraGetIssue idOrKey: 'GAR-21'
      echo issue.data.toString()
    }
  }
}
