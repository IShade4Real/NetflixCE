# NetflixCE

A modified cheat engine created exclusively for the purpose of injecting into Roblox, a reformed tool that bypasses previous Cheat Engine (CE) detections, enabling successful script injection. Please note that CE is limited to thread identity 2 as it runs via localscripts, but it can handle substantial scripts such as Infinite Yield. An internal executor is also provided to enhance your exploiting experience. It's important to clarify that a tool located in the player's backpack is required for injection. This is because the script runs through the LocalScript parented to the tool.


## Script Execution

Once downloaded, join the game link below and enter the game id you wish to join. Once teleported, open Netflix and a custom UI should pop up. Click Inject (Make sure a tool is located in your backpack) and wait for the lua engine to finish scanning memory addresses. Once the local script has been found, it should output "Inject: (Memory Address)". Simply hold the tool and an internal executor will load.

[Baseplate](https://www.roblox.com/games/15167092402/Baseplate)

## Built-in Scripts

To load infinite yield, run _G.IY() on the internal exec and click execute. Only a few scripts have been added though I do plan to add more.

(The web-client works but isn't 100% functional, you're experience may be different but if you do experience any problems use the Microsoft store version, bypasses hyperion so no need for downgrading) 

## Versions

### Version 2.0:

-- Added Dex Explorer support, run _G.dex() to load
-- Added blade ball functionality, to configure for blade ball, go to netflix folder --> autorun --> roblox.lua and place the file in another directory for example desktop, find the robloxbb.lua which should be in the netflix folder, place in the autorun folder then join blade ball , equip a ability other then dash and inject. Once injected, equip or re-equip the dash ability to load. (If it doesn't load instantly play a round with dash equipped)
-- _G.autoparry for blade ball auto parrying
-- Added a lumber tycoon money farm, _G.lt() to run
-- Added prison life script, _G.prisonlife()
-- Added a kohls admin house script, _G.CMDY()
-- Added process handler to prevent web client from crashing
(If crashes occur frequently, open netflix via the netflixprocesshandler.bat file)

## Credits

For privacy reasons i cant say who am i. Just remember me as "Shade"
I am not the original creator of this exploit. All credits go to [this guy.](https://github.com/IShade4ReaI)

# Q/A

Q: Will this ban me from roblox?

A: No, i tested this myself. I have an alt account where i keep using NCE and it havent got banned **currently** (i will update this incase it gets banned)

Q: Are you the original creator of NCE?

A: No. I cant say who am i, And no. Im not IShade4ReaI alternative account.

# Troubleshooting (Known issues & fixes)

## Missing DLL Error

You may get a Missing DLL error if you use "netflixcrashhandler". To fix that, remember the missing DLL name, go to google and search "Download *missing dll name*.dll". After this, a link from DLL-files.com should appear. Download the DLL 64x version, unpack the DLL and put it into System32. That should fix the issue (honestly did for me)

## Roblox crashing after injecting

After injecting into roblox, you might crash. If this happens, use the UWP version of roblox. However if you still crash after using UWP version of roblox, then try reinstalling it. (NOTE: i never had such a issue, so you might try to reinstall roblox to fix this. Otherwise roblox patched it and you can no longer use NCE)

## Error:attempt to index a nil value (local 'targetScript')

If you get this issue after injecting and getting an item, then you equipped an item without a LocalScript that is used to load the Executor. Try rejoining or re-injecting and then equipping a different item

## After injecting, it shows "Error:attempt to index a nil value (local 'targetScript')" but i didnt equip the tool

It automatically tries to get the tool's LocalScript and inject the code. Unfortunately i dont know the fix to this. Try using the UWP Version or joining through the Baseplate game.

## After i join and inject, it shows me a error without "Got tool: ...." etc.

Rejoin to fix this, Use the UWP Version or join through the Baseplate game (if you keep getting the same error, reinstall NCE or Roblox).
