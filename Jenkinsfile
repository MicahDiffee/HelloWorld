#!groovy

@Library('common@'common@1.0.0-100-100') _

import com.livingasone.enums.GkeCluster

gkeJavaPipeline (
	name: 'central',
	cluster: GkeCluster.US_CENTRAL1,
	test: [
		tasks: "test integrationTestDocker functionalTestDocker",
		requiresCompose: true
	],
	gradlePublish: true,
	swaggerPublish: true,
	cloudTestJobName: 'central-cloud-test'
)
