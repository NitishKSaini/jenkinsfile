node {
    checkout scm
    def customImage = docker.build("nitishsaini/my-image:${env.BUILD_ID}")
    customImage.push()
}
