@Library('mule-runtime-library@EE-7144') _

def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/metadata-model-api/master",
                               "Mule-runtime/mule-artifact-declaration/master" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "mavenSettingsXmlId" : "mule-runtime-maven-settings-MuleSettings",
                        "enableMavenTestStage" : false ]

runtimeProjectsBuild(pipelineParams)
