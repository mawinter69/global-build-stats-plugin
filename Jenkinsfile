#!/usr/bin/env groovy

/* `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library */
buildPlugin(
  useContainerAgent: true, // Set to `false` if you need to use Docker for containerized tests
  configurations: [
    [platform: 'linux', jdk: 17],
    [platform: 'linux', jdk: 21],
    [platform: 'windows', jdk: 11],
])
