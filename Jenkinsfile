/*
#!groovy

@Library('common@1.0-431') _

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
*/
