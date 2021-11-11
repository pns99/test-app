node {
    stage ("SCM Checkout") {
	    git "https://github.com/pns99/test-app"
	          	 
    }
    stage ("Compile-package") {
	    //mvntest
	def mvnHOME = tool name: 'mymaven', type: 'maven'
        sh "$mvnHOME}/bin/mvn package"
    }
}
