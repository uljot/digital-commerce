### Deployment

Ensure that following env variable exists

```bash
export P24_MERCHANT_ID=""
export P24_CRC=""
export P24_RETURN_URL=""
export P24_STATUS_URL="{your_url}/verify-payment"

```
```bash
mvn package
java -jar target/digital-commerce-1.0-SNAPSHOT.jar

#visit browser localhost:8080
```
