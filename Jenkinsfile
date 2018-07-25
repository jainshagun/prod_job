node {
  stage('JIRA') {
    withEnv(['JIRA_SITE=http://jira.sainsburysargos.io']) {
      def fields = jiraGetFields idOrKey: 'GAR-21'
      echo fields.data.toString()
    }
  }
}
