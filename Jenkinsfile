node {
    checkout scm
    
    stage("Say Hi"){
	echo "Hello world"
    }
    properties([
    parameters [ 
	    string(defaultValue: 'John Snow', description: 'who dies', name: 'NAME')
	]
    ])
}