VillagerPocket Gradle project
Target: Paper 1.21.8, Java 21

GitHub Actions workflow: .github/workflows/build.yml
Build locally: gradle build
Output: build/libs/VillagerPocket-1.0.0.jar

The workflow builds the project on pushes, pull requests, or manual dispatch,
then uploads the JAR as the VillagerPocket-JAR artifact.

Custom icon source is included at src/main/resources/icons/villagerpocket.png.
This PNG is included as a resource; Minecraft item textures require a resource pack
or server-supported custom model system to display it in-game.

Nitwit icon source is included at src/main/resources/icons/nitwit.png.
Pocket items now include the villager's formatted profession in the item name
(e.g. "Farmer Pocket Villager" or "Nitwit Pocket Villager"). The PNG is bundled
as a resource; displaying it as the actual Minecraft inventory texture requires
an accompanying resource pack or a supported custom-model setup.
