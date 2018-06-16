node {
        skipDefaultCheckout()
		
		checkout([$class: 'GitSCM', 				
					branches: [[name: "origin/master"]], 
					userRemoteConfigs: [[
					url: 'https://github.com/pipelineascode/node-skipDefaultCheckout.git']]
					])
		
		
		stage('Build'){		
			echo 'Hello World 1'
		}
}
