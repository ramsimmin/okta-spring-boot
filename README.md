# Configure okta properties

Update okta issuer and client_id defined in application.properties

```
okta.oauth2.issuer= https://{yourOktaDomain}/oauth2/default
okta.oauth2.client-id= {yourClientId}

```

# Build and run

```
mvn clean install
```

Run your application

