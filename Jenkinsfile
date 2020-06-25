node {

stage('Scm checkout') { 
  git 'https://github.com/kapilkinger/E2EProjectCucumber'
}

stage ('Compile-Package') {
	sh 'mvn package'
}

}
