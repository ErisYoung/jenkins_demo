stage('debug') {
    steps {
        // echo env.is_print_env
        script {
            if (env.is_print_env) {
                sh "printenv"
            } else {
               echo "no execute 'sh printenv'"
            }
        }
    }
}
