pipeline {
  agent any

  stages {    
    stage('TEST') {
      steps {
        ftpPublisher alwaysPublishFromMaster: false, masterNodeName: 'master', paramPublish: [parameterName: ''], continueOnError: false, failOnError: false, publishers: [[configName: 'Dev Diligend', transfers: [[asciiMode: false, cleanRemote: true, excludes: '', flatten: false, makeEmptyDirs: false, noDefaultExcludes: true, patternSeparator: '[, ]+', remoteDirectory: '/', remoteDirectorySDF: false, removePrefix: '', sourceFiles: '*.*']], usePromotionTimestamp: false, useWorkspaceInPromotion: false, verbose: true]]
      }
    }
  }
}
