# Dremio ARP Connector for Apache Hive

## Build and Installation

1. Run the following command in the root directory for the Connector (the connector that contains the *pom.xml* file): `./mvnw clean package`
2. Place the built JAR file (from the *target* folder) in the /jars/ directory of your Dremio installation.
3. Copy the JAR file to the /jars/3rdparty/ directory of your Dremio installation.
4. Restart Dremio
