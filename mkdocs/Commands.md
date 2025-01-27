Purpur adds a few new commands to the game.

???+ note "Note"
    When Essentials is installed, a few of the commands below will be overriden by Essentials. To use Purpur's commands instead, add this to the `disabled_commands` section of the Essentials config.
    ``` yaml
    disabled-commands:
      - ping
      - uptime
      - compass
    ```

## /purpur
- This command allows reloading the purpur.yml config and viewing the Purpur version.

- **examples**:
    - `/purpur reload` reloads purpur.yml without a restart
    - `/purpur version` shows the current version (same as `/version`)

- **permission**:
    - `bukkit.command.purpur`

## /ping
- This command allows viewing the ping of players. If you do not specify a player name or player entity selector (`@a`, `@r`, etc) it will show you your own ping.

- **examples**
    - `/ping` shows you your own ping
    - `/ping BillyGalbreath` shows you the ping of BillyGalbreath
    - `/ping @a` shows you the ping of all players
    - `/ping @r` shows you the ping of a random player

- **permission**:
    - `bukkit.command.ping`

## /uptime
- This command allows viewing the uptime of the server.

- **permission**:
    - `bukkit.command.uptime`

## /demo
??? info "Image of the Demo Screen 📷"
    ![Demo Screen](images/demo.png)
- This command shows the demo screen to players. If you do not specify a player name or player entity selector (`@a`, `@r`, etc) it will show the demo screen to yourself.

- **examples**
    - `/demo` shows you the demo screen
    - `/demo BillyGalbreath` shows BillyGalbreath the demo screen
    - `/demo @a` shows the demo screen to all players
    - `/demo @r` shows the demo screen to a random player

- **permission**:
    - `bukkit.command.demo`


## /credits
??? info "Image of the Credits screen 📷"
    ![Credits screen](images/credits.png)
- This command shows the credits screen to players. If you do not specify a player name or player entity selector (`@a`, `@r`, etc) it will show the credits screen to yourself.

- **examples**
    - `/credits` shows you the credits screen
    - `/credits BillyGalbreath` shows BillyGalbreath the credits screen
    - `/credits @a` shows the credits screen to all players
    - `/credits @r` shows the credits screen to a random player

- **permission**:
    - `bukkit.command.credits`

## /tpsbar
??? info "Image of the tpsbar in action 📷"
    ![TPSBar in action](images/bossbar.gif)
- This command shows a bossbar showcasing your current TPS/MSPT to players. If you do not specify a player name or player entity selector (`@a`, `@r`, etc) it will show the tpsbar to yourself.

- **examples**
    - `/tpsbar` shows you the tpsbar
    - `/tpsbar BillyGalbreath` shows BillyGalbreath the tpsbar
    - `/tpsbar @a` shows the tpsbar to all players
    - `/tpsbar @r` shows the tpsbar to a random player

- **permission**:
    - `bukkit.command.tpsbar`

## /compass
??? info "Image of the compass in action 📷"
    ![Compass in action](images/bossbar.gif)
- This command shows a bossbar showcasing the current direction faced to players. If you do not specify a player name or player entity selector (`@a`, `@r`, etc) it will show the compass to yourself.

- **examples**
    - `/compass` shows you the compass
    - `/compass BillyGalbreath` shows BillyGalbreath the compass
    - `/compass @a` shows the compass to all players
    - `/compass @r` shows the compass to a random player

- **permission**:
    - `bukkit.command.compass`
