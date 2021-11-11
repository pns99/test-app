node {
    stage ("SCM Checkout") {
        git url: "https://github.com/pns99/test-app.git"
            }
    stage ("Compile-package") {
        sh "/opt/maven/bin/mvn package"
    }
}
