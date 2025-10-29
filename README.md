# lib-notifications-sendgrid

SendGrid email adapter for Firefly Notifications.

## Install
```xml path=null start=null
<dependency>
  <groupId>com.firefly</groupId>
  <artifactId>lib-notifications-sendgrid</artifactId>
  <version>1.0.0-SNAPSHOT</version>
</dependency>
```

## Configuration (application.yml)
```yaml path=null start=null
sendgrid:
  apiKey: ${SENDGRID_API_KEY}
```

`from` is set in the `EmailRequestDTO`; CC/BCC/attachments are supported.
