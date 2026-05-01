# Hello Spring Boot API

Minimal Spring Boot API with one endpoint:

- `GET /hello`

Expected response:

```json
{
  "message": "Hello from Spring Boot"
}
```

## Run locally

If Maven is installed:

```powershell
mvn spring-boot:run
```

If you use Maven wrapper later:

```powershell
.\mvnw.cmd spring-boot:run
```

Open:

- `http://localhost:8080/hello`

## Test

```powershell
mvn test
```
