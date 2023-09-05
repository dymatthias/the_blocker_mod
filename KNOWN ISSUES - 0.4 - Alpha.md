### The Blocker Mod - Known Issues - Version 0.4 - Alpha

1. TBM features (both those overwritten and added by the mod) will generally not limit space on starting planets. Some will still apply their bonuses--homeworlds are good! All features can still be cleared, will need to be to make an ecumenopolis, and clearing them will remove basic resource districts. In the future, the mod will do a more holistic pass on starting planets to bring them into the mod's overall system.

2. Numerous events are still in testing and are deliberately unregistered in on_actions until they pass testing.

3. Clearance cost and time numbers are still work-in-progress and subjject to change.

4. There is currently no support for gestalt consciousnesses. The mod's basic features will work for gestalts, but as they don't get colonists they won't get any bonuses from them. Gestalt support will be added in the future once I decide how I want to approach it.

5. Colonist modifiers are applied only when you have colonists on the planet, mostly to cut down on clutter in the feature card. Almost all features have some benefit to your colonists as they explore. This will also cause numerous errors to be logged until the features settle and get cleaned up a bit.

6. Terraforming will do some very interesting things to your world, and may behave unpredictably. Most of the modded features should be eligible for re-roll, but none of TBM's features are synced with terraforming events yet.

7. Currently, TBM does not affect rare features (gases, motes, crystals) at all; however, the increased number of features can sometimes result in fewer of these spawning.

8. No AI weights have been implemented yet for any features, overwritten or custom. This will result in the AI bulldozing almost everything. On higher difficulties, the AI gets most of its resources from difficulty bonuses and vassals, and should be fine. On lower difficulties, it may have economic problems until the weights are implemented and the balance can be tested and tweaked.

9. Various "event" or unique planets will lack features on spawn. This primarily affects systems added via unique solar system initializers that would normally not have blockers, such as the Sea of Consciousness, the Superflare tomb world, and the Fallen Empire colonies and Holy Worlds. A fix for this is in the works but requires a couple extra steps to properly maintain compatibility and should be added with 0.5.

10. Dangerous Wildlife Hunter jobs are considered farmers until the full event chain is reworked.
