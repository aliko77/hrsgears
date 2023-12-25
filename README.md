# HRSGears-edited
A manual gear mode you can use for 0r-hudv2. Support is not provided. It is only an example.

# Hud Events
```
RegisterNetEvent("0r-hud:Client:SetManualGear", function(newGear)    
end)
TriggerEvent("hrsgears:SetManualMode", Koci.Client.HUD.data.vehicle.manualMode)
```

# HRSGears Event
```
RegisterNetEvent("hrsgears:SetManualMode", function(data)
    manualon = data
end)
```
