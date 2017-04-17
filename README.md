# Running-Information-Analysis-Service

This is a Spring Boot Project.

## Motivation
Provides running information analysis service based on runner's running information. Each RunningInformation has attributes:
```
runningId,
latitude,
longitude,
runningDistance,
totalRunningTime,
heartRate,
Timestamp,
userInfo
```
`userInfo` includes 
```
username,
address
```
## Usage
```
git clone https://github.com/wennicky/Running-Information-Analysis-Service.git
cd Running-Information-Analysis-Service
docker-compose up -d
mysql --host=127.0.0.1 --port=3306 --user=root --password=root
mvn clean install
cd target
java -jar ./target/running-information-analysis-service-1.0.0.BUILD-SNAPSHOT.jar
```
