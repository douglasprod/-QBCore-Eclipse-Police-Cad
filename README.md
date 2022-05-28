# QBCore-Eclipse-Police-Cad

## Requirements
- [QBCore](https://github.com/qbcore-framework/qb-core)

## Installation:
Put `eclipse_Cad` in your resources folder.
Ensure `eclipse_Cad` in your server cfg.
Insert sql dump(take in `eclipse_Cad`) in your db.
Add this column to `players`:
`cadInfo`
![image](https://user-images.githubusercontent.com/36680471/165324305-53caf1e1-f2a2-4920-9002-423dfa11e097.png)

Copy this for default value:

```json
{"onDuty":0,"adam":0,"onPanic":false,"callsign":"0","picture":null}
```

Configure `config.js` for change rank list or key triggers.

![image](https://user-images.githubusercontent.com/36680471/165324738-043d51c4-66ff-4e32-b79d-fe833b7fcd4c.png)


Then you can start your server.
For more questions douglasprod#6686 && https://discord.gg/8nXR6rfB2C
