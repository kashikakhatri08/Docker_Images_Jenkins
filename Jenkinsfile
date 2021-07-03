node {
    checkout scm
    def customImage = docker.build("python-hello_app:${env.BUILD_ID}")
	stage("test"){
		sh "docker run python-hello_app:${env.BUILD_ID}"
	}
	//customImage.run("--rm")
	//customImage.pull()
}
