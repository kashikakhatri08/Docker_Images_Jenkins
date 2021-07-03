node {
    checkout scm
    def customImage = docker.build("python-hello_app:${env.BUILD_ID}")
	docker.image("python-hello_app:${env.BUILD_ID}")
}
