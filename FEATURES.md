# **All currently available Features of Mittelbot**

### In the following list i'll show all currently avaiable features. This means, you don't have to request or ask for those features anymore!

----

<br>

## Moderation
----
    - ban [mention/userid] [time] [reason]
    - unban [userid] [reason]
    - infraction [id]
    - infractions [mention/userid]
    - kick [mention/userid] [reason]
    - mute [mention/userid] [time] [reason]
    - unmute [mention/userid] [reason]
    - warn [mention/userid] [reason]
    - purge [number of messages]

<br>

## Administration
----
    - settings [setting] [value] ( ...[more values] )
    - - settings welcomechannel [#channel]
    - - settings prefix [prefix]
    - - settings cmdcooldown [time]
    - - settings dmcau [boolean]
    - - settings dcau [boolean]
    - - settings joinroles [roles, ...]
    - - settings auditlog [#channel]
    - - settings messagelog [#channel]
    - - settings modlog [#channel]
    - - settings warnroles [role, ...]

    - mods [setting] [value] ( ...[more values] )
    - - mods mr|modroles [role] [(isAdmin)boolean] [(isMod)boolean] [(isHelper)boolean]

<br>

## Information
----
    - info ([mention])
    - ping
