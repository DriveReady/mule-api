def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/metadata-model-api/1.1.6-JUNE-DRY-RUN",
                               "Mule-runtime/mule-artifact-declaration/1.1.2-JUNE-DRY-RUN" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "mavenSettingsXmlId" : "mule-runtime-maven-settings-MuleSettings",
                       "projectType" : "Runtime" ]

runtimeBuild(pipelineParams)
