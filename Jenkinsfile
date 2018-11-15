pipeline {
  agent any

  stages {    
    stage('TEST') {
      steps {
        ftpPublisher alwaysPublishFromMaster: false, masterNodeName: 'master', paramPublish: [parameterName: ''], continueOnError: false, failOnError: false, publishers: [[configName: 'Dev Diligend', transfers: [[asciiMode: false, cleanRemote: true, excludes: '', flatten: false, makeEmptyDirs: false, noDefaultExcludes: true, patternSeparator: '[, ]+', remoteDirectory: 'C:\\inetpub\\dev-front', remoteDirectorySDF: true, removePrefix: '', sourceFiles: '*.*']], usePromotionTimestamp: false, useWorkspaceInPromotion: false, verbose: true]]
      }
    }
  }
}
