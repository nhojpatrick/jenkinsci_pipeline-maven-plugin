/*
 * `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library
 */
buildPlugin(
  // cannot use this with Docker tests
  useContainerAgent: false,
  configurations: [
    [ platform: "linux", jdk: "11" ],
    [ platform: "windows", jdk: "11" ]
  ]
)
