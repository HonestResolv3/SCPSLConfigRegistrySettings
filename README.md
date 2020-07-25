# SCP:SL Config Registry Settings
An in-depth documentation of every configuration setting in SCP: Secret Laboratory as of the Scopophobia release

### File Access
- Go to %appdata%/SCP Secret Laboratory/registry.txt (Make sure SCP: Secret Laboratory is closed before making changes, they will apply on the next restart)

### Notes
Format is: SettingName|::(SettingValue)
Examples: 
- 07menumode::-%(|::1
- 00y_invert::-%(|::false
- 06AudioSettings_Effects::-%(|::42.05

### The Settings
Setting Name | Setting Type | Supported Values | Description
:---: | :---: | :---: | :------
06gammavalue::-%( | Float | 0.000 - 2 | Sets the amount of brightness in the game
06Sens::-%( | float | 0.100 - 3 | Sets the amount of mouse sensitivty in the game
00y_invert::-%( | Boolean | true or false | Sets the choice of inversion of the mouse input in the game
07SavedResolutionSet::-%( | Integer | 0 - 20 | Sets the games resolution, starts at 640x480 and goes up to 2560x1440
07ScreenMode::-%( | Integer | 0 - 3 | Sets the application window type, starts at Exclusive Fullscreen and goes to Windowed
00gfxsets_vsync::-%( | Boolean | true or false | Sets the choice of monitor-restricted framerates in the game
07MaxFramerate::-%( | Integer | -1, 15, 30, 45, 60, 90, 120, 144, 165, 240 | Sets the max frames per second the game can run at, disabled if 00gfxsets_vsync::-%( is true, -1 = Unlimited, 15 = 15 FPS, and so forth
07gfxsets_textures::-%( | Integer | 0 - 3 | Sets the texture quality of textures in the game, 0 = Very High, 1 = High, 2 = Medium, 3 = Low
07gfxsets_maxblood::-%( | Integer | 0 - 9 | Sets the max number of blood decals in the game, 0 = 0, 1 = 10, 2 = 25, 3 = 100, 4 = 250, 5 = 400, 6 = 650, 7 = 800, 8 = 1000, 9 = 2000
00gfxsets_shadows::-%( | Boolean | true or false | Sets the choice of having shadows in the game
07gfxsets_shadres::-%( | Integer | 0 - 3 | Sets the quality of the shadows in the game
07gfxsets_shaddis_new::-%( | Integer | 0 - 2 | Sets the distance of shadow visibility in the game
00gfxsets_mb::-%( | Boolean | true or false | Sets the choice of having motion blur in the game
00gfxsets_cc::-%( | Boolean | true or false | Sets the choice of having color correction in the game
00gfxsets_aa::-%( | Boolean | true or false | Sets the choice of having anti-aliasing (no jagged edges on models/textures) in the game
07gfxsets_hp::-%( | Boolean | true or false | Sets the choice of having the game render light in the game
06AudioSettings_Master::-%( | Float | 0.000 - 1 | Sets the volume of all sounds in the game
06AudioSettings_Effects::-%( | Float | 0.000 - 1 | Sets the volume of sound effects in the game
06AudioSettings_VoiceChat::-%( | Float | 0.000 - 1 | Sets the volume of peoples voices (voice chat) in the game
06AudioSettings_MenuMusic::-%( | Float | 0.000 - 1 | Sets the volume of the menu music in the game
06AudioSettings_Interface::-%( | Float | 0.000 - 1 | Sets the volume of button clicks and hovers in the game
07MenuTheme::-%( | Integer | 0 - 3 | Sets the menu music type in game, starts at Default and goes to Classic
00MaintainSliderProportions::-%( | Boolean | true or false | Sets the choice of keeping the menu music and interface volumes the same
00ClassIntroFastFade::-%( | Boolean | true or false | Sets the choice of having the class text "you are now: (class)" fade away quicker
00HeadBob::-%( | Boolean | true or false | Sets the choice of having the camera bob while you walk and run
00ToggleSprint::-%( | Boolean | true or false | Sets the choice of sprinting by just pressing SHIFT once
00HealthBarShowsExact::-%( | Boolean | true or false | Sets the choice of seeing the exact HP number instead of Precentage in the health bar
00RichPresence::-%( | Boolean | true or false | Sets the choice of users being able to see you playing the game on Discord
00PublicLobby::-%( | Boolean | true or false | Sets the choice of having your Steam friends join you in game through Steam and/or the overlay
00HideIP::-%( | Boolean | true or false | Sets the choice of hiding your IP on the client console and other areas
00ToggleSearch::-%( | Boolean | true or false | Sets the choice of picking up items by just pressing E once
00ModeSwitchSetting079::-%( | Boolean | true or false | Sets the choice of changing the way you can play as SCP-079
00PostProcessing079::-%( | Boolean | true or false | Sets the choice of enabling the screen effects when playing as SCP-079
00translation_changed::-%( | Boolean | true or false | Tells the game if the translation was changed
07menumode::-%( | Integer | 0 - 2 | Sets the menu type for the game, 0 = Classic Menu, 1 = Default Menu, 2 = Fast Menu
00DisplaySteamProfile::-%( | Boolean | true or false | Sets the choice of letting users see your steam profile in game
00DNT::-%( | Boolean | true or false | Sets the choice of hiding your IP in the client (in-game) console
07W_2_0::-%( | Integer | 0 - 4 | The sight choice for the Epsilon-11 Rifle, 0 = None, 1 = Holo Sight, 2 = Blue Dot Sight, 3 = Night Vision Sight, 4 = Sniper Scope
07W_2_1::-%( | Integer | 0 - 4 | The barrel choice for the Epsilon-11 Rifle, 0 = None, 1 = Silencer, 2 = Muzzle Brake, 3 = Heavy Barrel, 4 = Muzzle Booster
07W_2_2::-%( | Integer | 0 - 4 | The other attachment choice for the Epsilon-11 Rifle, 0 = None, 1 = Gyroscopic Stabalizer, 2 = Ammo Counter, 3 = Laser, 4 = Flashlight
07W_1_0::-%( | Integer | 0 - 2 | The sight choice for the Project-90 SMG, 0 = None, 1 = Red Dot Sight, 2 = Holo Sight
07W_1_1::-%( | Integer | 0 - 3 | The barrel choice for the Project-90 SMG, 0 = None, 1 = Suppressor, 2 = Silencer, 3 = Muzzle Brake
07W_1_2::-%( | Integer | 0 - 3 | The other attachment choice for the Project-90 SMG, 0 = None, 1 = Flashlight, 2 = Laser, 3 = Ammo Counter
07W_3_0::-%( | Integer | 0 - 2 | The sight choice for the MP7 SMG, 0 = None, 1 = Holo Sight, 2 = Red Dot Sight
07W_3_1::-%( | Integer | 0 - 1 | The barrel choice for the MP7 SMG, 0 = None, 1 = Silencer
07W_3_2::-%( | Integer | 0 - 1 | The other attachment choice for the MP7 SMG, 0 = None, 1 = Ammo Counter
07W_5_0::-%( | Integer | 0 - 1 | The sight choice for the USP Pistol, 0 = None, 1 = Collimator
07W_5_1::-%( | Integer | 0 - 2 | The barrel choice for the USP Pistol, 0 = None, 1 = Silencer, 2 = Heavy Barrel
07W_5_2::-%( | Integer | 0 - 1 | The other attachment choice for the USP Pistol, 0 = None, 1 = Flashlight
07W_0_0::-%( | Integer | 0 | The sight choice for the USP Pistol, 0 = None
07W_0_1::-%( | Integer | 0 - 1 | The barrel choice for the USP Pistol, 0 = None, 1 = Silencer
07W_0_2::-%( | Integer | 0 - 1 | The other attachment choice for the USP Pistol, 0 = None, 1 = Flashlight
07graphics_api::-%( | Integer | 0 - 4 | The graphics/rendering choice for the game, 0 = Default/Auto, 1 = DX11 (Recommended), 2 = DX12 (Experimental), 3 = OpenGL, 4 = Vulkan (Experimental)
