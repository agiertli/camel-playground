## Reproducer

```bash
mvn quarkus:dev
```

Result:
```
2025-05-28 23:13:25,052 WARN  [org.apa.cam.com.tim.TimerConsumer] (Camel (camel-1) thread #3 - timer://yaml) Error processing exchange. Exchange[DEF3E308C1DA1A2-0000000000000000]. Caused by: [org.apache.camel.http.base.HttpOperationFailedException - HTTP operation failed invoking http://localhost:8080/account with statusCode: 404]: org.apache.camel.http.base.HttpOperationFailedException: HTTP operation failed invoking http://localhost:8080/account with statusCode: 404
```
