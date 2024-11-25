# Amélioration chargement de chunk

![Je ne vais nulle part.](oredict:oc:chunkloaderUpgrade)

L'amélioration de chargement de tronçons peut être installée sur des appareils (comme les [robots](../block/robot.md) et les [microcontrôleurs](../block/microcontroller.md)) pour leur permettre de garder le tronçon dans lequel ils sont - ainsi que les chunks environnants - chargés. Cela consomme de l'énergie, cependant. Le chargeur de tronçons peut être activé et désactivé par l'API du composant exposé à l'appareil.

Cette amélioration est automatiquement activée quand l'appareil est mis sous tension, et automatiquement désactivée quand l'appareil est éteint.
