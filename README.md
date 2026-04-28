# Arma Reforger Modding Notes

Helpful links, resources, and notes around the mil-sim Arma Reforger.

## My Tag

* `ASFF` - [https://community.bistudio.com/wiki/OFPEC_Tags_List](https://community.bistudio.com/wiki/OFPEC_Tags_List)

## World Notes

* ArmaReforger -> Prefabs -> Systems -> ScenarioFramework
* `Area` -> `Layer` -> `Slot`

## Helpful Tips

* Use `CTRL + DOWN ARROW` to move the selected item in the world map down to the ground.
* `*.et` files are entity prefabs.
* `GameModeSF` is Game Mode [Scenario Framework](https://community.bistudio.com/wiki/Arma_Reforger:Scenario_Framework)
* When you play or start from the camera position, you are not assigned a faction.  It is helpful for testing but anything that requires
a faction will not work.
* `GenericComponent` vs. `GameComponent` vs. `ScriptComponent` - https://community.bistudio.com/wiki/Arma_Reforger:Create_a_Component
* Client vs. Server data needs and replication - https://community.bistudio.com/wikidata/external-data/arma-reforger/EnfusionScriptAPIPublic/Page_Replication_Overview.html
* For slots, the z-axis or the blue arrow is where spawned objects like people or vehicles will point to start.
* In the World Editor, click "Camera" at the top of the screen.  Then increase the "Far Plane".  This will push the "fog" back and allow you to see
more of the landscape.

## References

### Modding and Scripting

* [https://www.youtube.com/@TPMTactical/videos](https://www.youtube.com/@TPMTactical/videos)
* [Tutorial for Coop Mission Setup](https://forums.bohemia.net/forums/topic/287110-tutorial-how-to-setup-a-coop-mission/)
* [https://www.youtube.com/@Blackheart_Six-script/videos](https://www.youtube.com/@Blackheart_Six-script/videos)
* [Official Bohemia Arma Reforger Modding Youtube Tutorial Series](https://www.youtube.com/watch?v=Fgl_mAHReP4&list=PLfUcrRpCM_fKjkTrkV-bqnknVbFCPA3YU)
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
* [Overthrow](https://github.com/ArmaOverthrow/Overthrow.Arma4)
* [Project Rebellion](https://github.com/FatihHekim0glu/Project-Rebellion)
* [HTCTI](https://github.com/HTomJMW/htCTI-Arma-Reforger)
* [Everon Life](https://github.com/EveronLife/EveronLife)
* [Bohemia Arma Reforger Samples](https://github.com/BohemiaInteractive/Arma-Reforger-Samples)

### Dedicated Server

* [Arma Reforger Dedicated Server in Docker](https://github.com/acemod/docker-reforger)
