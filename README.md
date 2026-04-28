# Arma Reforger Modding Notes

Helpful links, resources, and notes around the mil-sim Arma Reforger.

## My Tag

* `ASFF` - [https://community.bistudio.com/wiki/OFPEC_Tags_List](https://community.bistudio.com/wiki/OFPEC_Tags_List)

## Helpful Tips

### General

* Downloaded mods via the game are saved here: `C:\Users\<username>\Documents\My Games\ArmaReforger`
* Workbench mods via the Tools application are saved here: `C:\Users\<username>\Documents\My Games\ArmaReforgerWorkbench`

## World Notes

* ArmaReforger -> Prefabs -> Systems -> ScenarioFramework
* `Area` -> `Layer` -> `Slot`
* Tools -> Game Mode Setup is a helpful plugin that will walk you through the creation of common managers and systems that are needed
within the World Editor environment for your mission.
* Use `CTRL + DOWN ARROW` to move the selected item in the world map down to the ground.
* `*.et` files are entity prefabs.
* When you play or start from the camera position, you are not assigned a faction.  It is helpful for testing but anything that requires
a faction will not work.
* For slots, the z-axis or the blue arrow is where spawned objects like people or vehicles will point to start.
* In the World Editor, click "Camera" at the top of the screen.  Then increase the "Far Plane".  This will push the "fog" back and allow you to see
more of the landscape.
* Under the Plugins, you can launch a dedicated server with a client to help test server + client synchronization and data.

### Scripting

* `GameModeSF` is Game Mode [Scenario Framework](https://community.bistudio.com/wiki/Arma_Reforger:Scenario_Framework)
* `GenericComponent` vs. `GameComponent` vs. `ScriptComponent` - [see details on creating components on the wiki](https://community.bistudio.com/wiki/Arma_Reforger:Create_a_Component)
* When in the script editor, "Build" -> "Validate Scripts" will check all your custom scripts for any syntax errors or other issues.
* The `*.c` files which is the programming language specific to the Enfusion engine can be documented and then save documentation
via Doxygen.

### Replication

* Client vs. Server data needs and replication, [see details on the wiki](https://community.bistudio.com/wikidata/external-data/arma-reforger/EnfusionScriptAPIPublic/Page_Replication_Overview.html)
* RplChannels have `Reliable` and `Unreliable` similar to TCP and UDP in terms of whether they are guaranteed to be received or not.
* [The wiki has details on multiplayer scripting](https://community.bistudio.com/wiki/Arma_Reforger:Multiplayer_Scripting) and network considerations.

## References

### Modding and Scripting

* [https://www.youtube.com/@TPMTactical/videos](https://www.youtube.com/@TPMTactical/videos)
* [Tutorial for Coop Mission Setup](https://forums.bohemia.net/forums/topic/287110-tutorial-how-to-setup-a-coop-mission/)
* [https://www.youtube.com/@Blackheart_Six-script/videos](https://www.youtube.com/@Blackheart_Six-script/videos)
* [Official Bohemia Arma Reforger Modding Youtube Tutorial Series](https://www.youtube.com/watch?v=Fgl_mAHReP4&list=PLfUcrRpCM_fKjkTrkV-bqnknVbFCPA3YU)
  * Replication and Synchronization Between Client and Server
  * [Part 1](https://www.youtube.com/watch?v=asWxIIHT6d0)
  * [Part 2](https://www.youtube.com/watch?v=rTqb3QvndxA)
* [https://www.youtube.com/@blackheart_six-framework/videos](https://www.youtube.com/@blackheart_six-framework/videos)
* [https://github.com/Herbiie/ArmAReforgerMissionMakingGuide](https://github.com/Herbiie/ArmAReforgerMissionMakingGuide)
  * See Wiki page
* [https://www.youtube.com/@rabid-squirrel/videos](https://www.youtube.com/@rabid-squirrel/videos)
  * [Mission Scripting Example](https://www.youtube.com/watch?v=AaEkrhn-KCg)
    * [Corresponding Github Tutorial](https://github.com/AngusBethke/RS_ScriptingTutorial_1)
* [https://github.com/JacobMeister/ScenarioFrameworkExplained](https://github.com/JacobMeister/ScenarioFrameworkExplained)
* [Arma Reforger Scripting API Reference](https://community.bistudio.com/wikidata/external-data/arma-reforger/ArmaReforgerScriptAPIPublic/index.html)
* [Awesome Reforger - List of Helpful Links](https://github.com/ofpisnotdead-com/awesome-reforger)

### Interesting Projects

* [COE2](https://github.com/Kexanone/COE2_AR/)
* [Dynamic Operations](https://github.com/JacobMeister/DynamicOperations)
* [RHS - Status Quo](https://github.com/RHSMODS/statusquo)
* [Global Conflicts](https://github.com/Global-Conflicts-ArmA/gc-reforger-core)
  * [Global Conflicts Missions](https://github.com/Global-Conflicts-ArmA/gc-reforger-missions)
* [Overthrow](https://github.com/ArmaOverthrow/Overthrow.Arma4)
* [Project Rebellion](https://github.com/FatihHekim0glu/Project-Rebellion)
* [HTCTI](https://github.com/HTomJMW/htCTI-Arma-Reforger)
* [Everon Life](https://github.com/EveronLife/EveronLife)
* [Bohemia Arma Reforger Samples](https://github.com/BohemiaInteractive/Arma-Reforger-Samples)

### Dedicated Server

* [Arma Reforger Dedicated Server in Docker](https://github.com/acemod/docker-reforger)
