# List of Useful Retail Macro's
**Here I will post helpful macro's that you can use in-game for general gameplay or gold making.**

## General macro's

**3 mounts in one: This macro will let you cast one of the mounts that you add in the macro.**
```
#showtooltip
/cast [btn:3] Grand Expedition Yak
/cast [btn:2] Azure Water Strider
/cast X-53 Touring Rocket
```

**Mountspecial: This one will do a mountspecial on your mount.**
```
/mountspecial
```

**Reset Instance: This will reset the instance by clicking the macro. (Currently not working in Shadowlands, looking for a fix).**
```
/script ResetInstances();
```

**Leave party: By pressing this macro you will leave the group directly.**
```
/script C_PartyInfo.LeaveParty()
```

## Fury Warrior

**Cancel Bladestorm Macro. This macro allows you to cancel your Bladestorm early. You cannot cast other abilities while Bladestorming, so this can be useful if targets die during the channel.**
```
#showtooltip Bladestorm
/cancelaura Bladestorm
/cast Bladestorm
```

**Pummel Macro. This macro uses Pummel against your focus target, if you have one, or against your current target if you have no focus target.**
```
#showtooltip Pummel
/cast [@focus, harm, exists][@target] Pummel
```

**Automatic Heroic Leap. This will cast Heroic Leap where ever your cursor is located, without waiting for the targeting circle.**
```
#showtooltip Heroic Leap
/cast [@cursor] Heroic Leap
```

**Charge and Victory Rush. Because Charge is off the Global Cooldown, Victory Rush or any other melee ability can be used on the same keybind. When outside of melee range, Charge will be cast instead.**
```
#showtooltip
/cast Charge
/cast Victory Rush
```
