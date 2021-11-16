# Scaffolding

This would be a sample Spring boot project which would include various aspects of a spring boot microservice.
Following are the aspects which would be covered:
1. Application Structure (packaging)
2. Build tool(Gradle/maven) with appropriate dependencies/Preferably gradle
3. Dockerfile/ Also a docker compose to run the application independently on a local DB
4. kube.yml(Sample actual values of parameter would be decided based on the perf tests later)
5. Exception Handling.
6. Lombok.(better readablity of code and increases the coverage)
7. Logging.
8. Unit tests
8. Integration tests which can be executed independently.
9. Kafka Integration.(Spring has multiple integrations with Kafka and we would need to figure out which works best for us)
10. DB Scripts management through flyway which automates the complete DDL (Depending on the choice of DB)
//Keep Adding points to above in case we add something which is at a concern level in a common landscape.

