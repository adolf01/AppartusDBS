CZ:
Použité permise:
appartus.debuger = Uživatel s touto permisí může používat příkazy Appartusu a jeho funkce
appartus.block.* = Permise důležitá pro samotné blokování bloků ve hře
appartus.allow.* = Permise která dokáže povolit opřesňujíci blok

Příkazy:
/debugmode = Přepíná mezi režimy, detail bloku, permise pro daný blok a vypnuto. Funguje globálně pro všechny debugery najednou.
Když je debugmode aktivní v prvním nebo druhém režimu, tak pro debugery neplatí blokovací pravidla a mohou manipulovat se všemi bloky.
/bozimod = nesmrtelnost pro běžné případy, funguje pro každého debugera zvlášť do restartu.

Funkce:
Pomocí permisí uživatele a nebo skupiny můžeš blokovat:
    mód = appartus.block.minecraft = tohle zablokuje uživateli všechny bloky z modu Minecraft
    block = appartus.block.mineraft:log = tímhle se zablokují všechny typy a nebo varianty dřeva
    variant = appartus.block.minecraft:log:oak = tímhle se zablokuje konkrétní typ dřeva

Přepínání mezi debugmody se provádí jen napsáním příkazu /debugmode do chatu, v chatu se při tom hned vypíše aktuální režim.
Jakýkoliv debug mód lze používat jen s předmětem Carrot on a Stick (398) v hlavní ruce.
Kliknutím tímto předmětem na block se vám v debugmodu detail, vypíše kompletní název předmětu všetně detailů. V debugmodu permise se vám
vypíše permise nutná pro zablokování kliknutého bloku.

Plugin funguje se všemi forge mody pro minecraft.


EN:
Used permission:
appartus.debuger = User with this permis, can use commands and Appartus functions.
appartus.block. * = permis very important to lock the blocks in the game.

Orders:
/ DebugMode = Switch between modes, DETAIL MODE, PERSMISSION MODE for the block and OFFMODE. It works globally for all debuggers at once.
When DebugMode is active in the first or second mode, then blocking rules do not apply and debugers can manipulate with all Blocks.
/ Bozimod = immortality in normal cases, it works for debuggers to restart.

Function:
Using permission on a user or group, you can block:
    mode = = appartus.block.minecraft this block user all the blocks from the mode of Minecraft
    block = appartus.block.mineraft:log = this one disables all types and variants or wood
    options = appartus.block.minecraft:log:oak = this one block a specific type of wood
                                                        
Switching between DebugMode is done just by typing /DebugMode to chat, plugin displays to you in char current mode.
Any debugode can only be used with the subject Carrot on a Stick (398) in the primary hand.
Clicking with this Stick on Block in detail DebugMode, show you name of the Block including details of the subject. In DebugMode PERMISSION show you permis needed to lock clicked block.

The plugin works with all mods for minecraft forge.