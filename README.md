<img src="https://www.blackspigot.com/proxy.php?image=https%3A%2F%2Fi.imgur.com%2F3dF9NjI.png&hash=343119031dd15e79ff010be72e508ec1" alt="slalkk" />

SuperTrailsPro - Gives the project a new life. New code, new features, better performance, online features, multi-language support (every player decides which language they use).

<img src="https://www.blackspigot.com/proxy.php?image=https%3A%2F%2Fi.imgur.com%2Fqi9vnD7.png&hash=b57a564c11430759382c1f977f3c6b36" alt="slalkk" />

Plugin supports 1.8-1.17
What that's mean to you?
If you using 1.8: You get new patches, bug fixes, and features!
If you using 1.9+: All features, bugfixes from versions below + your MC version features

Custom Wings
It doesn't matter how many servers are using SuperTrails, your server is unique!
Create your wings, customize already build-in, download, share with others.

Wings Patterns
Only 3 colors? Not for you and your players! Apply images on wings to make it unbelievably beautiful!

Multi-languages support
Do you run a huge server for players from different countries? Let you players select their preferred language..

Everyone Invited To The Party!
Reward your regular and premium players with event boxes so they can to try their luck and win unique trails!

Custom Block Trails
Create your own block trails.

Vanish Support
Trails disappear while you are in vanish to hide you from players.
Invis potions supported.

Combat Hider
Hide trails while the player is in combat. So you can use the plugin even on pvp servers.

--Smart Sound System--
You can use 1.8 & 1.9+ sound names. Plugin will convert it automatically for your server version.

--Citizens Support--
Showcase trails with NPCs, looks fancy.


[IMG]

/Trails - Open trails GUI
/TrailsID <Name\ID> [Player] - Apply trail with command (trails.admin)
/TraildID Custom <Data> <Player> - Apply custom player data (trails.admin)
/SuperTrails - Show main supertrails menu
/SuperTrails event - Show event command list
/SuperTrails npcmode - Apply trail to Citizens NPC

[IMG]
Top #1 question been asked
Why I don't have any wings in wings selector?
Because plugin let you make custom wings/patterns there's no wings/patterns built in jar file. You should download default preset, its located below on this page under "After download" spoiler
Spoiler: FAQ and Tutorial links
How to create custom wings ? (UPDATED August 2019)

/trailsid tutorial

Trails\Mode\Color IDs

Change default language
- Swap your language id with English.yml id. Plugin use language with id 0 as default.
(Language ID located in language yml file)

How to give specific event trails to player?
- Visit Trails\Modes\Color IDs page, choose trail id that you need.
For example, want to add myself orange fairy trail : /supertrails event give kvqq 347

What is timed event?
- You can temporally let your player open few event chests for free
- /supertrails event timed <time in seconds> <chests amount>
- Usage example : /supertrails event timed 300 10

Start timed event for an hour or 30 minutes:
- /supertrails event timed H1 10
- /supertrails event timed M30 10
- Note: When you reload\restart server timed event stops


[IMG]
Spoiler: Permission list
trails.admin - Admin access

trails.alltrails - Allow all trails

Particle Trails
trails.allparticles - Allow all particle trails
trails.particle.heart
trails.particle.angry
trails.particle.magic
trails.particle.fun
trails.particle.cloud
trails.particle.green
trails.particle.witch
trails.particle.ender
trails.particle.spark
trails.particle.flame
trails.particle.white
trails.particle.note
trails.particle.snow
trails.particle.water
trails.particle.lava
trails.particle.crit
trails.particle.smoke
trails.particle.spell
trails.particle.enchant
trails.particle.splash
trails.particle.slime
trails.particle.snowball
trails.particle.void
trails.particle.lavapop
trails.particle.breath
trails.particle.endrod
trails.particle.damage
trails.particle.totem
trails.particle.soul
trails.particle.soulfire

Modes
trails.allmodes - Allow all modes
trails.mode.circle
trails.mode.magician
trails.mode.shooter
trails.mode.slinky
trails.mode.pulse
trails.mode.helix
trails.mode.dna

Block Trails
trails.allblocks - Allow all blocks
trails.block.1
trails.block.2
trails.block.3
trails.block.4
trails.block.5
trails.block.6
trails.block.7
trails.block.8

Wings
trails.allwings - Allow all wings
Permissions for custom wings trails.wings.<config key>
permissions for default wings
trails.wings.angel
trails.wings.butterfly
trails.wings.elf
trails.wings.long
trails.wings.butterfly2
trails.wings.short
trails.wings.demon
trails.wings.night

trails.keeper - allow players create quick wings sets

Patterns
trails.allpatterns - Allow all patterns
Permissions for custom patterns trails.pattern.<config key>
permissions for default patterns
trails.pattern.gradient1
trails.pattern.gradient2
trails.pattern.gradient3
trails.pattern.mushroom
trails.pattern.fire
trails.pattern.colors
trails.pattern.fly

Rains
trails.rains - Allow full access to rain builder
trails.rain.color.white (/black/red/yellow/green/blue/purple) - Allow cloud color
trails.rain.item.<item name> - Allow player pick item for rain trails

Other
trails.see - (Permission for OnlyPermittedPlayersCanSeeTrails; false by default in config)
trails.community.use - Let player use community (Except download & upload; staff permission) [Removed]
trails.community.upload - Let player upload files to community (staff permission) [Removed]
trails.community.download - Let player download files from community (staff permission) [Removed]
[IMG]

Spoiler: Config
Code (Text):
Options:
HideEnableMessage: false #In case you don't wanna see how much plugin loves you everytime
UpdateChecker: true
UpdateNotify: true #Notify admins for update
DetectInvisPotion: false #Hides trail when player uses invis potion, can be used to detect Essentials vanish
SuperVanish: false #Hides trail when player in vanish (Supports multiple vanish plugins)
EventTrails: true #(Special type of trails that player can get from "lootboxes")
HideInCombat: false #Hide trail when player gets damage
HideInCombatTime: 50 #Time period before trails appear again after player received damage (Require: HideInCombat)
NoRainItemNames: false #This option doesn't really do anything useful
RainsWithPackets: true #Plugins use magic of packets to create rains instead of making real items, better keep it true. Was useful before, just in case something goes wrong
BannedWorlds: #Don't wanna let players use trails in specific worlds?
Enable: false
Worlds:
- World1
HideOnMove: #Hide trail when player moves, HOW DARE THEY MOVE!
Enable: false
Particles: false
Rains: false
Event: false
Wings: false
SelectSounds: #Make them enjoy that BLUP sound when they select trail from menu
Enable: false
Particles: NOTE_PLING
Blocks: NOTE_PLING
Rains: NOTE_PLING
Wings: NOTE_PLING
Event: NOTE_PLING
SimpleFairiyAI: true #Dumb fairy eats less cpu resources, true perfered
LanguagesMenu: true #Language menu so players can choose their language
DefaultMode: 0 #Particle trail mode by default. Mode by default called "Default". Dont ask why.
PermissionChecker: #Papers please! You no longer have permission to use this trail, take it off now!
TimerChecker: false #Check players periodically
JoinChecker: false #Check on join
BroadcastEventMessages: true #Deliver message about your event to everyone
Inventory:
RemoveItem: PAPER
BackItem: ARROW
BackItemSlot: 49
RemoveItemSlot: 39
LanguageItem: 41
Particles: true
Blocks: true
Rains: true
Wings: true
ParticlesItem: BLAZE_POWDER
BlocksItem: STAINED_GLASS,3
RainsItem: GHAST_TEAR
WingsItem: FEATHER
ModesItem: ANVIL
LanguagesItemType: SLIME_BALL
ParticlesSlot: 19
BlocksSlot: 21
RainsSlot: 23
WingsSlot: 25
EventSlot: 4
ParticlesMenuSize: 54
MainMenuSize: 54
BlocksMenuSize: 54
PaneLines:
Particles: true
Blocks: true
Rains: true
Event: true
LanguageItemSlot: 41
OnlyPermittedPlayersCanSeeTrails: false #They are not allowed to see that beauty!
DisableSelectMessage: false #Hide it, nobody should know
ForceHighParticleSpawnRate: false #Make wings even more fancy but may affect players fps (Works only 1.13+, cuz there particles may drop fps)
HideNoPermissionTrails: false #Hide trails they shouldnt see (in menus)
ModeChanger: true
ForceDefaultMode: false #Sets default mode for all players when they join server
PreventGhostParticles: true #Servers running on low tps, experienced some random colored particles to appear on wings, true is recommended
RainItems:
- AIR;ENCHANTMENT_TABLE;ENDER_CHEST;WOOD_BUTTON;APPLE;DIAMOND;COAL;IRON_INGOT;AIR
- AIR;GOLD_INGOT;STRING;FEATHER;WHEAT;BREAD;PORK;GOLDEN_APPLE;AIR
- AIR;REDSTONE;PAPER;EGG;CAKE;COOKIE;MELON;EYE_OF_ENDER;AIR
- AIR;GHAST_TEAR;BOW;GOLD_NUGGET;EMERALD;NETHER_STAR;ANVIL;GOLDEN_APPLE:1;AIR
- AIR;WOOL:1;WOOL:2;WOOL:3;WOOL:4;WOOL:5;WOOL:6;WOOL:7;AIR
Modes:
Circle:
MovementSpeed: 30
Y: 2.2
Magician:
Y: 0.5
Shooter:
LiveTime: 25
Speed: 0.4
Slinky:
MaxFall: 5
Helix:
Radius: 4
ParticlesAmount: 40
Dna:
Disabled: true
Spiral:
Disabled: true
VerticalSpeed: 0.1
MovementSpeed: 30
Y: 0
Rotate90: true
MYSQL:
Enable: false
ip: ''
port: ''
database: ''
login: ''
password: ''
ParticleTrails:
Heart:
Slot: 10
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Angry:
Slot: 11
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Magic:
Slot: 12
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Fun:
Slot: 13
Speed: 1
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Cloud:
Slot: 14
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Witch:
Slot: 15
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Ender:
Slot: 16
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Green:
Slot: 17
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Spark:
Slot: 18
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Flame:
Slot: 19
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
White:
Slot: 20
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Note:
Slot: 21
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Snow:
Slot: 22
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Water:
Slot: 23
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Lava:
Slot: 24
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Crit:
Slot: 25
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Smoke:
Slot: 26
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Spell:
Slot: 27
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Enchant:
Slot: 28
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Splash:
Slot: 29
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Slime:
Slot: 30
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Snowball:
Slot: 31
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Void:
Slot: 32
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
LavaPop:
Slot: 33
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Breath:
Slot: 34
Speed: 0.1
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Damage:
Slot: 35
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
EndRod:
Slot: 36
Speed: 0
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
Totem:
Slot: 37
Speed: 0.1
Y: 0
Amount: 4
OffsetX: 1
OffsetY: 1
OffsetZ: 1
BlockTrails:
'1':
Version: S18 #Minimal version required to for this block trail
Item: '95:0'
ItemNew: WHITE_GLASS
Set: 35,14,35,4,35,5,35,3
Slot: 10
'2':
Version: S18
Item: '95:1'
ItemNew: ORANGE_GLASS
Set: 95,0,95,1,95,2,95,3
Slot: 11
'3':
Version: S18
Item: '95:2'
ItemNew: MAGENTA_GLASS
Set: 153,0,112,0,87,0,89,0
Slot: 12
'4':
Version: S18
Item: '95:3'
ItemNew: LIGHT_BLUE_GLASS
Set: 159,1,159,2,159,8,159,6
Slot: 13
'5':
Version: S18
Item: '95:4'
ItemNew: YELLOW_GLASS
Set: 21,0,129,0,73,0,16,0
Slot: 14
'6':
Version: S18
Item: '95:5'
ItemNew: LIME_GLASS
Set: 46,0,33,0,25,0,152,0
Slot: 19
'7':
Version: S18
Item: '95:6'
ItemNew: PINK_GLASS
Set: 3,2,2,0,13,0,12,0
Slot: 20
'8':
Version: S18
Item: '95:7'
ItemNew: SILVER_GLASS
Set: 42,0,41,0,57,0,133,0
Slot: 21
Wings:
Angel:
File: wing.png #File (wings/models/)
Slot: 19
Item: '288:0' #Support numeric ids and text ids (both legacy and new)
Butterfly:
File: Butterfly.png
Slot: 20
Item: '288:0'
Elf:
File: Elf.png
Slot: 21
Item: '288:0'
Long:
File: Long.png
Slot: 22
Item: '288:0'
Butterfly2:
File: Butterfly2.png
Slot: 23
Item: '288:0'
Short:
File: Short.png
Slot: 24
Item: '288:0'
Demon:
File: Demon.png
Slot: 25
Item: '288:0'
Night:
File: Night.png
Slot: 25
Item: '288:0'
WingsPatterns:
Gradient1:
File: pattern.png
Slot: 19
Item: '160:10'
Gradient2:
File: g2.png
Slot: 20
Item: '160:4'
Gradient3:
File: pattern1.png
Slot: 21
Item: '160:9'
Mushroom:
File: mushroom.png
Slot: 22
Item: '160:14'
Fire:
File: Fire.png
Slot: 23
Item: '160:1'
Colors:
File: colors.png
Slot: 24
Item: '160:10'
Fly:
File: bf.png
Slot: 25
Item: '160:11'
