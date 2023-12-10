![2023-12-09-the-vantage-READMEMD](https://github.com/owlboy/vantage-public/assets/237349/d3d11e58-4287-409d-b857-3261ec864879)

### This Repository
This repository is the public sister repository to the private repository for The Vantage.

#### Bug Reports and Feature Requests
Feel free to use the [issues](https://github.com/owlboy/vantage-public/issues) feature of this repository to report bugs or make feature requests relating to The Vantage.

### Change Log
#### 2023.12.09 - The Vantage
* Added a video screen Render Texture resolution toggle for lowering the default resolution - 4k/2k

#### 2023.12.01 - The Vantage
* Added holiday decorations
* Adjusted lighting
* Adjusted reflection probe intensity
* Updated AudioLink to v1.2
* Updated com.vrchat.worlds to v3.4.1
* Updated com.vrchat.base to v3.4.1
* Misc minor changes and adjustments

#### 2023.11.05
* Removed halloween decorations
* Misc minor changes and adjustments

#### 2023.10.22 - The Vantage
* Added custom gimmicks for a showing of The Tingler (1959)

#### 2023.10.01 - The Vantage
* Decorated for Halloween 2023!

#### 2023.09.24 - The Vantage
* Overhauled lighting profile
* Misc minor changes and adjustments

#### 2023.09.09 - The Vantage
* Added audio occlusion for voices via [UdonVoiceUtils](https://github.com/Guribo/UdonVoiceUtils)

#### 2023.07.22 - 2023.07.31 - The Vantage
* Implemented an Avatar Scaling configuration
* Updated the scripts controlling audio falloff and frequency cutoffs for the theater speakers
* Updated to com.vrchat.worlds 3.2.2
* Updated to com.vrchat.base 3.2.2
* Updated to com.vrchat.core.vpm-resolver 0.1.21

#### 2023.06.30 - The Vantage
* Refactored how the houselights are controlled
* Restored On and Off buttons for the houselights
* Fixed the global reflection probe
* Tweaked some materials
* Misc minor changes and fixes
  
#### 2023.06.19 - The Vantage
* Addressed issues with my production scripts that lead to playback errors 🫠
* Overhauled the speaker system! - Thanks for the guidance and input [Hackspanner](https://github.com/hackspanner) !
* Updated the screen to support aspect ratios wider than 16x9
* Added subtitle functionality via [USharpVideo-Subtitles](https://github.com/jacklul/USharpVideo-Subtitles) - Thanks [_Haï~](https://twitter.com/vr_hai) & [jacklul](https://github.com/jacklul) !
* Reimplemented the screen glow toggle
* Improved the reload button to provide visual feedback and prevent reload spamming
* Overhauled the chairs in the theater with a rebuilt and improved model
* Addressed an issue where light maps on light bulbs using Silent's Fake Glass shader would have a disproportionate performance impact on users that were supersampling. (They didn't need to be light mapped)
* Spider-plant! Spider-plant!
* Tweaked various materials
* Performed performance comparisons between Unity 2019 and Unity 2021
* Misc minor changes and fixes

#### 2023.05.22 - The Vantage
* Fixed an issue that prevented the main theater door from automatically closing during screenings.

#### 2023.05.16 - The Vantage
* Verified that all Metallic texture files are using the proper import settings. – [thegreatpug.com/help/srgb/](https://thegreatpug.com/help/srgb/)
* Verified that all textures are using streaming mipmaps. – [thegreatpug.com/help/streaming-mipmaps/](https://thegreatpug.com/help/streaming-mipmaps/)
* Recompiled my custom shaders with the latest version of Amplify Shader Editor.
* Miscellaneous minor changes and fixes.

#### 05/13/23 - The Vantage
* Fixed collision near the playback controls.
* Fixed missing lightprobes in the Theater room - Thanks Mimi!
* Adjusted occlusion settings so edge case situations can't occlude the screen. – Thanks Not Rishi!
* Upgraded to com.vrchat.worlds 3.2.0.
* Upgraded to com.vrchat.base 3.2.0.
* Upgraded to com.vrchat.udonsharp 1.1.8.
* Upgraded to com.vrchat.clientsim 1.2.4.
* Upgraded to com.vrchat.core.vpm-resolver 0.1.19.
* Upgraded to the latest version of Filamented.

#### 05/11/23 - The Vantage
* Expanded the theater room by one chair width.
* Made miscellaneous minor changes.

#### 02/15/20 - 05/01/23 - The Vantage
* Upgraded to Unity 2019.
* Updated to latest SDKs as they became available.
* Recreated most previous world functionality with Udon.
* Implimented UdonSharpVideo and integrated it with my front end and back end systems.
* Upgraded to VRChat Creator Companion.
* Restored dynamic poster functionality via the VRCSDK ImageLoader.
* Refined the new back room further - Note: The back room is still in Early Access.
* Migrated to [Filamented](https://gitlab.com/s-ilent/filamented) shader due to the [broken albedo meta pass](https://github.com/Xiexe/XSEnvironmentShaders/issues/9) in Xiexe's XSEnvironmentShaders.
* Added a new VHS tape for Madman Movie Night - "Show me your dick."
* Added a [spatula](https://www.youtube.com/watch?v=2XbCWmY0eqY).
* Completely relit and decorated the world for Halloween 2022.
* Decorated for the Winter Holidays for 2020, 2021, 2022.
* Added new posters.
* Added/rearranged shaders.
* Reimplemented Station functionality for the tiny chairs in the theater.
* Improved and fixed many lightmap UVs.
* Improved light probes.
* Optimized reflection probe update rate.
* Held Madman Movie Night every week.
* Screened various VJ mixes that I have produced over the last few years - `Vantage Mix - Alpha`, `Vantage Mix - Beta`, `Vantage Mix - If Ever… Now`, `Vantage Mix - Fracture Free Edition`, `Vantage Mix - Feb 2023`.
* Hosted many live VJ events utilizing my backend video library of over 666 videos.
* Fractured my arm.
* Made many miscellaneous changes and updates.

#### 01/30/19 - 02/15/20 - The Vantage
* Initiated the creation of a new room behind the theater.
* Fixed disappearing Udon boxes in the new room.
* Implemented many miscellaneous changes and updates.

#### 01/20/19 - 01/30/20 - The Vantage
* Executed many optimization fixes.
* Installed wood paneling.
* Applied many performance fixes.
* Added new posters.
* Added new VHS tapes.
* Set up Christmas Decor during Christmas.
* Installed timecode display.
* Designed custom displays for events.
* Made many other miscellaneous changes.

#### 01/19/19
* Reintroduced the door with a toggle feature.
* Ensured the door occludes the other room properly when closed.
* Reduced overdraw from the floor.
* Updated lightmap UVs on the chairs in the theater.
* Added a picture from Legend of the Guardians.
* Installed a proper mirror frame.
* Updated carpet border in Mirror Room.
* Aligned the carpet in the lounge area/mirror room.
* Removed banner for Pub Crawl.

#### 01/18/19
* Installed banner for Pub Crawl.

#### 11/19/18
* Fixed strange reflection probes.
* Simplified light probes.
* Updated FIVE SIX poster.
* Fixed overly red bounce lighting on chairs.
* Tweaked lights in the theater.

#### 11/18/18
* Relit the main theater to be darker when nothing is playing.
* Added a new FIVE SIX poster.
* Introduced a toggle for the theater seats for Full Body Tracking users.
* Fixed the screen glow so it can fade down with the screen (Thanks for the tip, Printer!).
* Fixed the flickering theater light.
* Fixed missing objects when you respawn out of the theater.
* Improved the screen glow to hopefully reduce flickering.
* Updated the ball.
* Fixed object sync on the drawers.
* Fixed tiny chairs so you can exit them properly.
