pipeline {
    agent {
        docker { image 'jekyll/jekyll:3.8' }
    }
    stages {
        stage('Build') {
            steps {
                // sh 'docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8 jekyll serve'
            }
        }
        tage('Test') {
            steps {
                echo 'Testing'
                // sh 'docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8 jekyll serve'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
                // sh 'docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8 jekyll serve'
            }
        }
    }
}