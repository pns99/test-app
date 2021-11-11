node {
    stage ("SCM Checkout") {
        git url: "https://github.com/pns99/test-app.git"
            }
    stage ("Compile-package") {
	    //mvntest
	def mvnHOME = tool name: 'mymaven', type: 'maven'
        sh "$mvnHOME}/bin/mvn package"
    }
}
