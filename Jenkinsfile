post {
    success {
        emailext(
            to: 'adarshmetgud059@gmail.com',
            subject: 'Build SUCCESS',
            body: 'Amazon project build completed successfully!'
        )
    }

    failure {
        emailext(
            to: 'adarshmetgud059@gmail.com',
            subject: 'Build FAILURE',
            body: 'Amazon project build has failed. Check Jenkins Console Output.'
        )
    }
}
