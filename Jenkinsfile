
def runcode() {
    node {
       stage "Run test."
       sh "./src/aisatsu.sh"
       stage "Do something."
       sh "./test/dosometin.sh"
    }
}

node() {
    stage "Checkout"
    checkout scm
}


runcode()



