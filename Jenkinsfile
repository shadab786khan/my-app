node {
	stage('Get repository"){
	git https://github.com/shadab786khan/my-app.git
	      }
	      stage('Build Package'){
		      def mvhHome = tool name: 'mavan3', type: 'maven'
			      sh "${mvhHome}/bin/mvn package"
	      }
}
