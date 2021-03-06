---
id: EnablePlayerCameraTarget
title: EnablePlayerCameraTarget
description: Toggle camera targeting functions for a player.
tags: ["player"]
---

:::warning

This function was added in SA-MP 0.3.7 and will not work in earlier versions!

:::

## Description

Toggle camera targeting functions for a player. Disabled by default to save bandwidth.

| Name     | Description                                                    |
| -------- | -------------------------------------------------------------- |
| playerid | The ID of the player to toggle camera targeting functions for. |
| enable   | 1 to enable camera targeting functions and 0 to disable them.  |

## Returns

1: The function executed successfully.

0: The function failed to execute. The player is not connected.

## Examples

```c
public OnPlayerConnect(playerid)
{
     EnablePlayerCameraTarget(playerid, 1);
     return 1;
}
```

## Related Functions

- [GetPlayerCameraTargetVehicle](../functions/GetPlayerCameraTargetVehicle): Get the ID of the vehicle a player is looking at.
- [GetPlayerCameraTargetPlayer](../functions/GetPlayerCameraTargetPlayer): Get the ID of the player a player is looking at.
- [GetPlayerCameraFrontVector](../functions/GetPlayerCameraFrontVector): Get the player's camera front vector
