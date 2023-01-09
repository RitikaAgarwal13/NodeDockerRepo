node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("ritikaagarwal01/nodedocker")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}