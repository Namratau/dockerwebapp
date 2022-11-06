node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'namratautekar') {

        def customImage = docker.build("namratautekar/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
