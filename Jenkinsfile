def workspace = manager.build.getEnvVars()["workspace"]

new File("workspace").eachFileMatch(~/."Jenkinsfile"/){file ->
	println file.getName()
}
