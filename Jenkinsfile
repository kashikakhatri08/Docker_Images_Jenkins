node {
    checkout scm
    def customImage = docker.build("python-hello_app:${env.BUILD_ID}")
	customImage.run()
	customImage.inside{
		sh "python --version"
		sh "python ./index.py"
	}
}
