"# vibium" 
Prerequisite - Vibium requires Java 11 or higher (we recommend the latest LTS). Check if you have it:
1. Clone the repo
2. Download dependencies 
cd vibium


# Download the vibium JAR and its dependency (Gson)
curl -LO https://repo1.maven.org/maven2/com/vibium/vibium/26.3.18/vibium-26.3.18.jar
curl -LO https://repo1.maven.org/maven2/com/google/code/gson/gson/2.11.0/gson-2.11.0.jar
3.Run 
	-Gradle - gradle run
	-maven - mvn compile exec:java -Dexec.mainClass=Hello