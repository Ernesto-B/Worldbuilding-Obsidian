# WorldForge: Interactive Map-Centric Wiki Platform for Dungeons & Dragons Campaigns

## Introduction

### Elevator Pitch

WorldForge is a cutting-edge platform designed to revolutionize how Dungeon Masters (DMs), players, and enthusiasts track and interact with their Dungeons & Dragons (D&D) campaigns. Centered around an interactive world map, WorldForge seamlessly integrates campaign progression, character development, and rich worldbuilding into a single, visually engaging experience. Built for extensibility and multi-campaign synchronization, it allows players to explore their adventures as a living atlas while enabling DMs to manage progression with precision. Whether you are running one campaign or building a sprawling shared universe with multiple DMs, WorldForge offers unparalleled control and immersion.

### Detailed System Overview

WorldForge is a map-centric interactive wiki platform tailored for D&D campaigns, acting as a living atlas that tracks every element of a campaign world. Each location on the map acts as an entry point into detailed information such as characters, lore, session recaps, shops, and factions. Sessions are recorded and represented visually as paths on the map, with DMs able to reveal regions progressively through a fog-of-war system.

Multiple campaigns can exist within the same world, with a multi-campaign visibility system ensuring that players and spectators only see progress up to their respective campaign’s latest session. DMs can pin world events visible across all campaigns, creating a shared evolving universe. Players can also contribute personal map markers and session logs, fostering engagement and ownership over their journey.

The system is built from the ground up with extensibility as a core principle, enabling future enhancements without compromising existing functionality.

### Use Cases

- **Single DM Campaign:** A DM uses the platform to track their homebrew campaign, revealing locations over time and logging the party’s journey.
- **Shared World, Multiple DMs:** Two or more DMs run separate campaigns in the same world. Progress is tracked per campaign, with players seeing only their campaign’s progress while DMs maintain cross-campaign oversight.
- **Spectator Access:** Non-players follow along as spectators, viewing the world map and unlocked lore in real-time as sessions unfold.
- **Collaborative Worldbuilding:** Trusted collaborators contribute to the world’s development by adding lore entries, fleshing out regions, or populating cities with characters and shops.
- **World Events:** DMs pin major world events that affect all campaigns, ensuring that global shifts in the setting are communicated across groups.

---

## Features and Requirements

### Functional Requirements

|Requirement ID|Description|
|---|---|
|FR-01|Allow DMs to create, manage, and reveal map regions as players progress.|
|FR-02|Enable freehand drawing of session paths on the map, representing the party’s journey.|
|FR-03|Implement a fog-of-war system to hide and reveal map areas.|
|FR-04|Provide multi-campaign support, ensuring players see only their campaign’s progress while DMs see everything.|
|FR-05|Allow DMs to pin global world events visible to all campaigns.|
|FR-06|Enable players to add personal map markers and contribute to session logs.|
|FR-07|Support the creation of nested location entries (NPCs, shops, lore, factions, items) tied to map regions.|
|FR-08|Grant collaborators the ability to add and modify lore entries within assigned regions.|
|FR-09|Provide spectator access to view the campaign’s revealed world and progression without editing capabilities.|
|FR-10|Ensure user roles (DM, Player, Collaborator, Spectator) govern access and functionality appropriately.|

### Nonfunctional Requirements

|Requirement ID|Requirement Description|
|---|---|
|NFR-01|The platform must be designed with modular extensibility to accommodate future features with minimal refactoring.|
|NFR-02|The system must scale to support multiple concurrent campaigns and DMs within the same world.|
|NFR-03|Data consistency must be maintained when updating map regions, session paths, or world events.|
|NFR-04|The platform must prioritize a user-friendly interface with smooth map navigation and intuitive content editing.|
|NFR-05|Data access permissions must be strictly enforced based on user roles and campaign visibility rules.|

### System Features, Key Considerations, and Goals

- **Session Path Overlay:** Freehand drawing tool for precise journey representation; editable for corrections.
    
- **Session-Based Visibility:** Cross-campaign visibility logic ensing players can only
    
    see up to their latest session; DMs see everything.
    
- **World Event Pins:** Global events pinned by DMs to synchronize impactful changes across campaigns.
    
- **Fog-of-War Exploration:** Progressive area reveals to simulate exploration.
    
- **Nested Wiki Structure:** Locations act as hubs containing NPCs, items, shops, and lore.
    
- **Role-Based Access Control:** DMs manage campaigns, players contribute content, collaborators enrich worldbuilding, spectators observe.
    
- **Modularity and Extensibility:** Designed for seamless integration of future content types, mechanics, or visualization tools.
    

---

## Other Considerations

### Differentiation from Existing Platforms

| Platform    | Key Limitation                                                                                     | How WorldForge Stands Out                                                |
| ----------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Obsidian.md | File-based, lacks map-centric journey tracking.                                                    | Fully integrated map as the primary interface.                           |
| World Anvil | Rich lore-building but limited in real-time campaign journey tracking and session overlays.        | Combines worldbuilding with live session tracking on an interactive map. |
| Roll20      | Focused on virtual tabletop play, not session recap, lore-building, or multi-campaign progression. | Complements gameplay by **Snap-to-Road Paths:** Optional purney mapping. |

### Potential Issues, Drawbacks, and Concerns

- **ComplexitPlayer Perspectives:** Allow players to upload personal hand-drawn maps reflecting their character’s perception**stency Risks:** Cross-campaign data (e.g., a world event) could introduce synchronization issues if not handled carefully.
- **Freehand Path Accuracy:** Drawing paths manually may be cumbersome without an intuitive drawing interface.

### Future Enhancements Beyond MVP

- **Session Path Animation**: Playback of journeys to visualize party travel dynamically.
- **Player-Specific Notes:** Private annotations visible only to specific players.
- **Snap-to-Road Paths:** Toggleable path snapping along pre-marked roads for smoother path visualization.
- **Player Perspectives:** Allow players to upload personal hand-drawn maps reflecting their character’s perception at a specific location.
- **Session Replay:** Interactive replay showing the sequence of map reveals and session path progression over time.
- **Quest System Integration:** Assign and track quests, linking them to map markers and session logs.

### Additional Notes

- **Cross-Campaign Narratives:** Potential to introduce story arcs spanning multiple parties and DMs.
- **Data Portability:** Support for exporting campaign data and map paths for offline storage or backup.

---

## Conclusion

WorldForge aims to bridge the gap between worldbuilding, session tracking, and collaborative storytelling through a map-centric platform tailored for Dungeons & Dragons campaigns. Its extensible architecture and cross-campaign visibility system ensure it can scale alongside ambitious shared-world projects, setting it apart as an indispensable tool for DMs, players, and fantasy enthusiasts alike.](<# WorldForge: Interactive Map-Centric Wiki Platform for Dungeons & Dragons Campaigns

## Introduction

### Elevator Pitch

WorldForge is a cutting-edge platform designed to revolutionize how Dungeon Masters (DMs), players, and enthusiasts track and interact with their Dungeons & Dragons (D&D) campaigns. Centered around an interactive world map, WorldForge seamlessly integrates campaign progression, character development, and rich worldbuilding into a single, visually engaging experience. Built for extensibility and multi-campaign synchronization, it allows players to explore their adventures as a living atlas while enabling DMs to manage progression with precision. Whether you are running one campaign or building a sprawling shared universe with multiple DMs, WorldForge offers unparalleled control and immersion.

### Detailed System Overview

WorldForge is a map-centric interactive wiki platform tailored for D&D campaigns, acting as a living atlas that tracks every element of a campaign world. Each location on the map acts as an entry point into detailed information such as characters, lore, session recaps, shops, and factions. Sessions are recorded and represented visually as paths on the map, with DMs able to reveal regions progressively through a fog-of-war system.

Multiple campaigns can exist within the same world, with a multi-campaign visibility system ensuring that players and spectators only see progress up to their respective campaign’s latest session. DMs can pin world events visible across all campaigns, creating a shared evolving universe. Players can also contribute personal map markers and session logs, fostering engagement and ownership over their journey.

The system is built from the ground up with extensibility as a core principle, enabling future enhancements without compromising existing functionality.

### Use Cases

- **Single DM Campaign:** A DM uses the platform to track their homebrew campaign, revealing locations over time and logging the party’s journey.
- **Shared World, Multiple DMs:** Two or more DMs run separate campaigns in the same world. Progress is tracked per campaign, with players seeing only their campaign’s progress while DMs maintain cross-campaign oversight.
- **Spectator Access:** Non-players follow along as spectators, viewing the world map and unlocked lore in real-time as sessions unfold.
- **Collaborative Worldbuilding:** Trusted collaborators contribute to the world’s development by adding lore entries, fleshing out regions, or populating cities with characters and shops.
- **World Events:** DMs pin major world events that affect all campaigns, ensuring that global shifts in the setting are communicated across groups.

---

## Features and Requirements

### Functional Requirements

| Requirement ID | Description                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------- |
| FR-01          | Allow DMs to create, manage, and reveal map regions as players progress.                                      |
| FR-02          | Enable freehand drawing of session paths on the map, representing the party’s journey.                        |
| FR-03          | Implement a fog-of-war system to hide and reveal map areas.                                                   |
| FR-04          | Provide multi-campaign support, ensuring players see only their campaign’s progress while DMs see everything. |
| FR-05          | Allow DMs to pin global world events visible to all campaigns.                                                |
| FR-06          | Enable players to add personal map markers and contribute to session logs.                                    |
| FR-07          | Support the creation of nested location entries (NPCs, shops, lore, factions, items) tied to map regions.     |
| FR-08          | Grant collaborators the ability to add and modify lore entries within assigned regions.                       |
| FR-09          | Provide spectator access to view the campaign’s revealed world and progression without editing capabilities.  |
| FR-10          | Ensure user roles (DM, Player, Collaborator, Spectator) govern access and functionality appropriately.        |

### Nonfunctional Requirements

| Requirement ID | Requirement Description                                                                                           |
| -------------- | ----------------------------------------------------------------------------------------------------------------- |
| NFR-01         | The platform must be designed with modular extensibility to accommodate future features with minimal refactoring. |
| NFR-02         | The system must scale to support multiple concurrent campaigns and DMs within the same world.                     |
| NFR-03         | Data consistency must be maintained when updating map regions, session paths, or world events.                    |
| NFR-04         | The platform must prioritize a user-friendly interface with smooth map navigation and intuitive content editing.  |
| NFR-05         | Data access permissions must be strictly enforced based on user roles and campaign visibility rules.              |

### System Features, Key Considerations, and Goals

- **Session Path Overlay:** Freehand drawing tool for precise journey representation; editable for corrections.
- **Session-Based Visibility:** Cross-campaign visibility logic ensing players can only

  &#x20;see up to their latest session; DMs see everything.
- **World Event Pins:** Global events pinned by DMs to synchronize impactful changes across campaigns.
- **Fog-of-War Exploration:** Progressive area reveals to simulate exploration.
- **Nested Wiki Structure:** Locations act as hubs containing NPCs, items, shops, and lore.
- **Role-Based Access Control:** DMs manage campaigns, players contribute content, collaborators enrich worldbuilding, spectators observe.
- **Modularity and Extensibility:** Designed for seamless integration of future content types, mechanics, or visualization tools.

---

## Other Considerations

### Differentiation from Existing Platforms

| Platform    | Key Limitation                                                                                     | How WorldForge Stands Out                                                                            |
| ----------- | -------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Obsidian.md | File-based, lacks map-centric journey tracking.                                                    | Fully integrated map as the primary interface.                                                       |
| World Anvil | Rich lore-building but limited in real-time campaign journey tracking and session overlays.        | Combines worldbuilding with live session \*\*tracking on a\*\***n inte\*\*\*\*rac**\*\*t\*\*ive map. |
| Roll20      | Focused on virtual tabletop play, not session recap, lore-building, or multi-campaign progression. | Complements gameplay by **Snap-to-Road Paths:** Optional purney mapping.                             |

### Potential Issues, Drawbacks, and Concerns

- **Complexit\*\*\*\*Player Perspectives:** Allow players to upload personal hand-drawn maps reflecting their character’s perception**stency Risks:** Cross-campaign data (e.g., a world event) could introduce synchronization issues if not handled carefully.
- **Freehand Path Accuracy:** Drawing paths manually may be cumbersome without an intuitive drawing interface.

### Future Enhancements Beyond MVP

- **Session Path Animation**: Playback of journeys to visualize party travel dynamically.
- **Player-Specific Notes:** Private annotations visible only to specific players.
- **Snap-to-Road Paths:** Toggleable path snapping along pre-marked roads for smoother path visualization.
- **Player Perspectives:** Allow players to upload personal hand-drawn maps reflecting their character’s perception at a specific location.
- **Session Replay:** Interactive replay showing the sequence of map reveals and session path progression over time.
- **Quest System Integration:** Assign and track quests, linking them to map markers and session logs.

### Additional Notes

- **Cross-Campaign Narratives:** Potential to introduce story arcs spanning multiple parties and DMs.
- **Data Portability:** Support for exporting campaign data and map paths for offline storage or backup.

---

## Conclusion

WorldForge aims to bridge the gap between worldbuilding, session tracking, and collaborative storytelling through a map-centric platform tailored for Dungeons & Dragons campaigns. Its extensible architecture and cross-campaign visibility system ensure it can scale alongside ambitious shared-world projects, setting it apart as an indispensable tool for DMs, players, and fantasy enthusiasts alike.>)