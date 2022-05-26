**Introduction**
<pre>
This is my Final Year Project in my bachelor degree of computer science in CUHK,
which supposed to be a souls-like RPG game.
Although there are disputs with my teamate
(which find out my teamate did not play any souls-like genre xd),
it is still a quite successful RPG game. (if not matter on artistic level)

The game is too big that exceed github transmission limit,
but I am lazy for the GitLFS.
Meanwhile, the game is not great enough to be my "game" portfolio
as the models and arts are not good.
Though, it shall be a good "code" portfolio.
Please view the details in those report if interested.
</pre>

**What I have participated on whole year**
<pre>
Basic architure:
    (Own Coding:)
        Main, graphic and sound setting menus and related functions
        Player status Save & Load system with multi-memory-slots
        Loading, pause screen and related functions
        GameState Manager
    (Third-party:)
        Camera control (by Unity Cinemachine)
        Camera real time cutscene (by Unity Cinemachine)
        Input System (by the new Unity default Input System 1.0.0)
        Post-processing (by Unity)

Gameplay:
    (Own Coding:)
        Player locomotion controll and animator handler
        Weapon System
        Combat system (Melee attack, combos and shield defense)
        Bonfire (reset player, world and AI status, fast travelling, save game)
        All player and AI's hitbox and hurtbox handler
        Ragdoll physics effect for some AI's dead body
    (Third Party:)
        Multi-player: Invasion (by Photon)

AI:
    (Own Coding:)
    Based on the simple AI made by partner, which is zombie like chase and attack
    I built advanced AI on top of his archiecture: (below all know strafing)
        Knight AI (AI with shield)
        AI with ranged auto-aim attack
        AI who knows keeping distance with player and have ranged attack
        Mimic
        Boss (AI with homing missile or rush if too far from player)

Sound:
    (Own Coding:)
        Footstep Sound
    (Third-party:)
        Spatial Sound Effect (by Valve)
    
Levels:
    (Own Coding:)
        Additive scene loading
        Doors in level 1 and Elevator
        Map data saving (i.e. memorizing unlocked door)
    (Both own coding & third party:)
        All level editing
    (Third party:)
        Doors in level 2
        Auto-changed post-processing (Leave/get in in-door environment)

</pre>