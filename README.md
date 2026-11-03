# Theme - Puzzle
# Modifiers - No Combat

Puzzle Boxed - https://zayd-game-dev.itch.io/puzzle-boxed 

## About The Project

**Puzzle Boxed** is a single-player, first-person 3D puzzle game built in **Unity 6 (6000.3.8f1)** with the Universal Render Pipeline (URP) and the Input System. Inspired by games like *Keep Talking and Nobody Explodes*, the game puts you in a room where you must inspect and interact with a mysterious locked box before the timer runs out.

### Gameplay

- **First-Person Controller** – Explore the room in first person with smooth movement and interaction.
- **Interact With The Box** – Inspect the box, open it, and work through its puzzles by looking closely, rotating pieces, and flipping switches.
- **Multiple Puzzle Types**:
    - **Circuit Connection** – The inside of the box reveals a broken circuit; rotate and connect pieces correctly to power it up.
    - **Number Sequence** – Discover the hidden code by figuring out the correct number sequence.
    - **Word Cipher** – The final code is hidden in notes found around the room; decode the phrase or combination to activate the box.
    - **Light Switches** – Toggle switches in the correct order.
- **Time Limit** – Beat the clock. Solve the final puzzle before time expires.
- **No Combat** – Pure puzzle solving; the challenge comes from observation and logic, not fighting.
- **Win Condition** – Solve the final puzzle to win the game.

### Structure & Scenes

- Different scenes cover the **Main Menu**, **Gameplay**, and **Level End** states.
- Gameplay data (puzzle definitions and settings) is driven by **ScriptableObjects**, making puzzles easy to create and extend.
- The UI is built with TextMesh Pro and the Skymon icon pack.

### Screenshots

| Main Menu | Gameplay |
| --- | --- |
| ![Main Menu](screenshots/main-menu.png) | ![Gameplay](screenshots/gameplay.png) |

| Puzzle – Circuit | Level End |
| --- | --- |
| ![Circuit Puzzle](screenshots/puzzle-circuit.png) | ![Level End](screenshots/level-end.png) |

> **Adding screenshots:** Upload your gameplay screenshots into a `screenshots/` folder at the project root with the file names used above (`main-menu.png`, `gameplay.png`, `puzzle-circuit.png`, `level-end.png`), and they will automatically be displayed here. You can also paste screenshots directly into GitHub's web editor — GitHub will handle the hosting for you and update these links.

## Project Folder Structure

```
Puzzle Boxed/
├── Assets/
│   ├── InputActions/          # New Input System action maps (.inputactions)
│   ├── Materials/             # Materials used across the game
│   ├── Models/                # 3D models (furniture pack) & .blend source files
│   ├── Prefabs/               # Reusable prefab objects (player, box, interactables)
│   ├── Scenes/
│   │   └── GameScene/         # Main menu, gameplay, and level-end scenes
│   ├── ScriptableObjects/     # Data-driven puzzle definitions and settings
│   ├── Scripts/
│   │   ├── ScriptableObjects/ # ScriptableObject classes
│   │   └── UI/                # UI-related scripts (menus, HUD, timers)
│   ├── SkymonIconPackFree/    # Free UI icon pack
│   ├── Sounds/
│   │   ├── Music/             # Background music tracks
│   │   └── SFX/               # Sound effects (clicks, footsteps, bells, locks)
│   ├── TextMesh Pro/          # TMP essentials (fonts, shaders, sprites)
│   ├── Textures/              # Texture files
│   └── URP/                   # Universal Render Pipeline settings
├── Packages/                  # Unity package manifest (dependencies)
├── ProjectSettings/           # Unity project configuration
├── UserSettings/              # Per-user editor settings
└── README.md                  # This file
```

## Game Idea
* Game like Keep talking and Nobody explodes - Interacting with a box
* Single Player
* FPS Controller
* Solve the final Puzzle to win
* Time Limit
* Different scenes for main menu, level end.
* Puzzle Ideas:
    - Circuit Connection – The inside of the box reveals a broken circuit, and you must rotate and connect pieces correctly to power it up.
    - Number Sequence - Hidden Code
    - Word Cipher – The final code is hidden in notes found around the room, requiring you to decode a phrase or combination to activate the box.
    - Light Switches - Toggle switches in the correct order

### Assets

Models
* https://mehrasaur.itch.io/3d-furnitre-pack

UI
* https://assetstore.unity.com/packages/2d/gui/icons/skymon-icon-pack-free-282424#description

Music
* Music by <a href="https://pixabay.com/users/freegroove-20279938/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=198357">Francesco Biondi</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=198357">Pixabay</a>, https://pixabay.com/music/crime-scene-detective-stories-198357/

SFX
* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=6776">freesound_community</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=6776">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-success-bell-6776/

* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=29401">freesound_community</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=29401">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-crouching-and-getting-up-dress-29401/

* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=29401">freesound_community</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=29401">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-concrete-footsteps-1-6265/

* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=36275">freesound_community</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=36275">Pixabay</a>, https://pixabay.com/sound-effects/household-inventory-grab-36275/

* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=40018">freesound_community</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=40018">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-button-press-40018/

* Sound Effect by <a href="https://pixabay.com/users/universfield-28281460/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=383961">Universfield</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=383961">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-computer-mouse-click-02-383961/

* Sound Effect by <a href="https://pixabay.com/users/freesound_community-46691455/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=76079">freesound_community</a> from <a href="https://pixabay.com/sound-effects//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=76079">Pixabay</a>, https://pixabay.com/sound-effects/household-lock-unlock-door-76079/

* Sound Effect by <a href="https://pixabay.com/users/dragon-studio-38165424/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=323619">DRAGON-STUDIO</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=323619">Pixabay</a>, https://pixabay.com/sound-effects/film-special-effects-soothing-white-noise-323619/


