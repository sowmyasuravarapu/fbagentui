// This shows a simple example of how to archive the build output artifacts.
node {
        stage('Checkout SCM'){
                git branch: 'master', url: 'https://github.com/sowmyasuravarapu/fbagentui.git'
        }

        stage('Install node modules'){
                sh "npm install"
        }
        stage('Build'){
                sh "npm run build"
        }
        stage('Deploy'){
                sh "ng serve"
        }
}
