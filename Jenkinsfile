node {
  stage('JIRA') {
    withEnv(['JIRA_SITE=http://jira.sainsbur']) {
      def fields = jiraGetFields idOrKey: 'GAR-21'
      echo fields.data.toString()
    }
  }
}
