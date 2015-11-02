node {
	
	println "pretend to build...";

	step([$class: 'FireEventStep', eventName: 'build', properties: """upstreamSha1=${env.GIT_COMMIT}"""]);
}