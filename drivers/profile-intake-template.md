# One-Click Driver Profile Intake

For the next Calesa driver profile, send this:

```text
Driver profile:

Name:
Zone:
Vehicle type:
Brand:
Model:
Color:
Plate:
Service tier:
Service zones:
Carnet ID:

Photos:
1. Driver portrait
2. Vehicle photo
```

Implementation rule:

1. Use this exact site: `Calesaweb/drivers/index.html`.
2. Add only one object in `Calesaweb/drivers/data.js`.
3. Copy images into `Calesaweb/drivers/assets/`.
4. Public page URL format: `drivers/?id=driver-id`.
5. Telegram/share preview URL format: `drivers/driver-id.html?v=<commit-or-date>`.
6. Do not publish the full carnet ID. If needed, publish only the last 4 digits.

Current example:

Page URL:

`drivers/?id=lizandro-guzman-hernandez`

Telegram/share URL:

`drivers/lizandro-guzman-hernandez.html?v=8a192b6`
