# Choosing a Map Projection

| Projection Category        | Properties                                                                                                                                                                | Common Uses                                                                            |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| Conformal                  | Preserves local shapes and angles                                                                                                                                         | Topographic maps, navigation charts, weather maps                                      |
| Equivalent (or Equal Area) | Preserves area                                                                                                                                                            | Thematic maps, dot density maps                                                        |
| Equidistant                | Preserves distance from one or two specified points to all other points on the map                                                                                        | Map of airline distances, seismic maps showing distances from an earthquake eipicenter |
| Azimuthal                  | All directions are true from a single specified point (usually centered on the map) to all other points                                                                   | Navigation and route planning maps                                                     |
| Compromise                 | None of these properties is preserved faithfully; relatives areas,  angles, and distances are all distorted to some degree, so that none are  distorted to a large degree | World maps, usually with distortion minimized near the center and along the equator    |

Some additional remarks:

* No map can be *both* **conformal** *and* **equivalent**.
* For a very localized projection (such as a State Plane zone), the difference between a **conformal** and **equivalent** projection is negligible.

