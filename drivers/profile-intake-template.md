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
4. Public URL format: `drivers/?id=driver-id`.
5. Do not publish the full carnet ID. If needed, publish only the last 4 digits.

Current example:

`drivers/?id=lizandro-guzman-hernandez`
