# HRSGears-edited
A manual gear mode you can use for 0r-hudv2. Support is not provided. It is only an example.

# Hud Events
```
RegisterNetEvent("0r-hud:Client:SetManualGear", function(newGear)
    Koci.Client.HUD.data.vehicle.manualGear = newGear
end)
TriggerEvent("hrsgears:SetManualMode", Koci.Client.HUD.data.vehicle.manualMode)
```

# HRSGears Event
```
RegisterNetEvent("hrsgears:SetManualMode", function(data)
    manualon = data
end)
```
## Thanks and Credits

- [@HugoSimoes12345]([https://github.com/HugoSimoes12345/HRSGears]) tasarım ve geliştirme için.
