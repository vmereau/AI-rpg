---
stepsCompleted: [1, 2, 3, 4]
session_active: false
workflow_completed: true
inputDocuments: []
session_topic: 'AI-powered browser RPG with LLM-generated narrative, visuals, and structured game mechanics'
session_goals: 'Design the full player experience: adventure initialization, choice-driven progression, structured combat/shop/spell systems, AI content generation, and narrative arc culminating in boss encounter'
selected_approach: 'ai-recommended'
techniques_used: ['Morphological Analysis', 'What If Scenarios', 'SCAMPER Method']
ideas_generated: 78
context_file: ''
---

# Brainstorming Session Results

**Facilitator:** Valentin
**Date:** 2026-02-12

## Session Overview

**Topic:** AI-powered browser RPG with LLM-generated narrative, visuals, and structured game mechanics

**Goals:** Design the full player experience -- adventure initialization, choice-driven progression, structured combat/shop/spell systems, AI content generation, and narrative arc culminating in boss encounter

### Context Guidance

_No external context file provided._

### Session Setup

**Key Design Pillars Identified:**

1. **Adventure Initialization** -- Player-influenced LLM generation of story, hero, spells
2. **Choice-Driven Progression** -- ~3 choices per step leading to varied event types (combat, loot, NPC/merchant)
3. **Structured Mechanics** -- Turn-based combat, stat systems (HP, Mana...), spell effects with stat trade-offs, shop/inventory economy
4. **AI-Generated Content** -- Text + images at every step, fully dynamic
5. **Narrative Arc** -- 5-10 steps building toward a major villain/boss encounter

## Technique Selection

**Approach:** AI-Recommended Techniques
**Analysis Context:** AI-powered browser RPG with focus on full player experience design

**Recommended Techniques:**

- **Morphological Analysis (Phase 1 - Foundation):** Systematically map all game system parameters and their possible values to ensure comprehensive coverage of the design space
- **What If Scenarios (Phase 2 - Idea Generation):** Blow open the structural map with radical "what if" questions across every game pillar to generate surprising, memorable ideas
- **SCAMPER Method (Phase 3 - Refinement):** Stress-test the best ideas through seven transformation lenses to produce actionable game features

**AI Rationale:** The project requires both structural completeness (many interconnected systems) and creative boldness (AI-generated narrative must feel alive). This sequence moves from comprehensive mapping → wild exploration → focused refinement.

## Technique Execution Results

### Phase 1: Morphological Analysis -- Parameter Mapping (30 ideas)

**[Stats #1]**: Hero/Opponent Stat System -- Archetype-driven stats (HP, Mana, Defense, Damage) with XP/level progression that scales based on archetype.
**[Spells #2]**: Dual-Target Spell Effects -- Spells modify stats (hero or opponent) positively or negatively. Unified stat-delta system.
**[Events #3]**: Four-Type Event System -- Combat, Treasure, Merchant, Story Event (wildcard fork).
**[Economy #4]**: Gold + Equipment + Inventory -- Gold from combat/events, simple inventory, equipment screen, contextual shopkeeper.
**[Arc #5]**: Escalating Danger Curve -- Start low-stakes, escalate through choices and leveling.
**[Init #6]**: Player-Seeded LLM Generation -- Player types seed phrase, LLM builds entire adventure world from it.
**[Choices #7]**: 3-Choice Branching Loop -- 3 choices → event → 3 new choices, contextually informed.
**[Tech #8]**: Free-Tier AI APIs -- Text + image generation via Gemini, GPT, or Claude free tiers.
**[Init #9]**: Sequential Generation with Re-Roll -- Flow: Story → Hero → Spells, re-rollable at each step.
**[Arc #10]**: Villain Established at Story Generation -- Big bad introduced at story generation, throughline for entire adventure.
**[Combat #11]**: Turn-Based Action System -- Basic Attack, Cast Spell (costs Mana/HP/other), Use Item.
**[Combat #12]**: Simple Opponent AI (Extensible) -- Enemies use LLM-driven decisions, architecture open for future complexity.
**[Equipment #13]**: Primary + Flex Stat Gear -- Weapons always +Damage, Armor always +Defense, both can have secondary stats.
**[Equipment #14]**: Trinket Slots -- 2 Rings + 1 Collar -- Three trinket slots for build-crafting.
**[Equipment #15]**: Rarity + Elite Encounters -- Equipment rarity tiers, higher rarity from elite fights or expensive shops.
**[Spells #16]**: Archetype Spell Tree -- 3 spells per archetype, unlocked at level 1/5/10 milestones. All visible from start.
**[Spells #17]**: Wild Spells -- Non-archetype spells found in treasure or magical merchants, enable hybrid builds.
**[Progression #18]**: 10-Level Cap with Milestone Gating -- Max level 10, key milestones at 1/5/10.
**[Spells #19]**: Unlimited Spell Access, One Cast Per Turn -- All spells available, pick one per combat turn.
**[Merchant #20]**: Thematic Shop Inventory -- Shop stock driven by shopkeeper profession (alchemist, blacksmith, etc).
**[Economy #21]**: Combat Loot as Sell Fodder -- Fights drop junk loot sellable at shops for gold.
**[Merchant #22]**: Shop as Choice Every Other Step -- Every other step, one of 3 choices leads to merchant.
**[Choices #23]**: Shop as Tactical Choice -- Shopping competes with combat/treasure/story. Trade-off baked into choice system.
**[Tech #24]**: Rolling Context Summary -- Each LLM call gets initial story setting + compressed summary of player choices.
**[Tech #25]**: Rich Image Generation -- Images for choices, character portraits for every entity.
**[Tech #26]**: Speculative Pre-Generation -- Pre-generate next choices while player is engaged in current step.
**[Tech #27]**: Generation Pipeline Architecture -- Generate text → images in parallel → pre-generate branches.
**[Tech #28]**: Aggressive Image Generation -- Full visual coverage, every moment illustrated.
**[Mechanics #29]**: Permadeath with Restart Options -- Death = restart same adventure (level 1) or generate new adventure.
**[Scope #30]**: No Save, No History -- Session-based, pure stateless play in browser memory.

### Phase 2: What If Scenarios -- Creative Exploration (35 ideas)

**[WhatIf #31]**: Active Villain Interference -- Villain acts during the adventure: sending assassins, cursing gear, taunting through NPCs. Escalates over time.
**[WhatIf #32]**: Blind Choices with Visual/Text Clues -- Choices don't label event type. Player deduces from text + image.
**[WhatIf #33]**: Fair Deception -- Clues Always Present -- Deceptive choices always contain at least one honest clue.
**[WhatIf #34]**: Hidden Morality -- World Tone Shifts -- Hidden morality value colors narrative tone, NPC attitudes, shop prices, visual aesthetic.
**[WhatIf #35]**: Morality Shapes the Boss Encounter -- Final fight influenced by morality: allies, villain dialogue, possible alliance offer.
**[WhatIf #36]**: Dynamic LLM-Driven Pricing -- No price tables. LLM sets prices based on full context.
**[WhatIf #37]**: Wild Spells as Pure Upside -- Found spells are always positive, no downsides.
**[WhatIf #38]**: Tone Slider for Adventure Generation -- Silly ↔ Serious slider alongside seed input.
**[WhatIf #39]**: LLM-Driven Boss Combat AI -- Boss uses full-context LLM decisions via structured JSON.
**[WhatIf #40]**: Structured JSON Combat Interface -- Combat returns action + narration in one JSON call.
**[WhatIf #41]**: Unified LLM Combat AI with Tiered Intelligence -- All combat uses LLM: regular=simple, elite=moderate, boss=tactical genius.
**[WhatIf #42]**: Enemy Intelligence as Emergent Difficulty -- Difficulty through smarter enemy behavior, not just stat inflation.
**[WhatIf #43]**: Narrative Continuity Through Choice Memory -- LLM references earlier events when generating new steps.
**[WhatIf #44]**: Rare Narrative Interrupts -- Optional dream/flashback/environmental events between steps, LLM-decided timing.
**[WhatIf #45]**: LLM-Triggered Event Timing -- System doesn't roll dice, LLM senses narrative pacing for interrupts.
**[WhatIf #46]**: Generated Hero Identity -- Name + appearance generated, appearance doubles as image prompt for consistency.
**[WhatIf #47]**: Player-Selected Art Style from Presets -- Curated art style list (painterly, pixel art, dark ink, etc).
**[WhatIf #48]**: Persistent Visual Style Bible -- Style context injected into every image call for coherence.
**[WhatIf #49]**: Narrated Combat Turn Log -- Enemy actions get LLM narration in combat log.
**[WhatIf #50]**: Combat JSON Extended Format -- Single call returns mechanical decision + narration field.
**[WhatIf #51]**: Clean Combat Log -- Player actions mechanical, enemy actions narrated.
**[WhatIf #52]**: Straightforward Loot from Events -- Treasure is direct reward, no sub-choices.
**[WhatIf #53]**: Full Hero Inspection Panel -- Persistent access to all hero stats, gear, spells, gold.
**[WhatIf #54]**: Hidden Adventure Progress -- Player never sees step count, boss arrives narratively.
**[WhatIf #55]**: No Near Death Mechanic -- Clean consistent combat, no special triggers at low HP.
**[Tech #56]**: Single JSON State Object -- Entire adventure as one JSON in browser memory.
**[Economy #57]**: Shops as Pure Buy/Sell -- No services, no crafting, just transactions.
**[UX #58]**: Zero-Friction Landing Page -- Seed (optional), tone slider, art style picker, Begin Adventure button. All defaults work.
**[Arc #59]**: Fixed Adventure Length -- Predictable step count for balanced pacing.
**[Progression #60]**: Front-Loaded Level Curve -- Max level reached early enough for power fantasy in final stretch.
**[Scope #61]**: Single Player Only -- No multiplayer, pure solo focus.
**[Arc #62]**: 20-Step Adventure with Boss at Step 21 -- Full adventure is 20 steps + boss encounter.
**[Progression #63]**: Max Level at Step 15 (Accelerated by Elite Fights) -- Standard curve hits 10 by step 15, elite fights accelerate.
**[UX #64]**: Scene Description + Scene Image + Choice Text -- Three layers per step: narrative, visual, decision.
**[UX #65]**: Full Visual Choice Presentation -- 4 images per step: scene + 3 choice previews.

### Phase 3: SCAMPER Method -- Refinement (13 ideas)

**[SCAMPER #66]**: Combat-Influenced Morality -- Combat behavior (sparing enemies, dark spells) feeds hidden morality alongside narrative choices.
**[SCAMPER #67]**: Equipment as Narrative Identity -- LLM references equipped gear in narrative, NPC reactions, villain dialogue.
**[SCAMPER #68]**: Shops as Safe Havens -- Shops are always reliable, no corruption or villain interference at merchants.
**[SCAMPER #69]**: Fixed 3-Choice System -- Always exactly 3 choices, no variation. Consistency is a feature.
**[SCAMPER #70]**: No Junk Loot -- Direct Gold from Combat -- Combat rewards gold directly. Inventory holds only meaningful items.
**[SCAMPER #71]**: Inventory Stays -- Clean but Present -- Inventory holds consumables and unequipped gear. Simple but gives player agency.
**[SCAMPER #72]**: Discoverable Boss Weakness -- Clues about villain vulnerability woven into narrative. Rewards attentive players.
**[SCAMPER #73]**: Boss Uses Current Fight Context Only -- Boss AI tactical in real-time, no meta-knowledge of player history.
**[SCAMPER #74]**: Morality-Flavored Spell Discovery -- Wild spells found match morality: dark path finds blood magic, light path finds heals.
**[SCAMPER #75]**: Clean Restart -- No Meta-Narrative -- Restart is a pure reset, no acknowledgment of previous attempts.
**[SCAMPER #76]**: Finite Consumables -- Potions/buffs have set quantity, use them and they're gone.
**[SCAMPER #77]**: Mana Reset Per Combat + In-Fight Recovery -- Full Mana at fight start, potions/spells for mid-fight recovery.
**[SCAMPER #78]**: Persistent HP Across Adventure -- HP carries over between steps, health potions are essential survival tools.

## Idea Organization and Prioritization

### Thematic Organization

**Theme 1: Adventure Initialization & Landing**
- Zero-Friction Landing Page (#58) -- Seed (optional), tone slider, art style picker, one button
- Player-Seeded LLM Generation (#6) -- Text seed influences all generation
- Tone Slider (#38) -- Silly to Serious axis
- Art Style Presets (#47) -- Player picks visual style from curated list
- Sequential Generation with Re-Roll (#9) -- Story+Villain → Hero → Spells, re-rollable
- Generated Hero Identity (#46) -- Name + appearance for portrait consistency
- Persistent Visual Style Bible (#48) -- Art style + hero/villain appearance injected into every image call

**Theme 2: Hero System (Stats, Progression, Spells)**
- Archetype-Driven Stats (#1) -- HP, Mana, Defense, Damage, scaling by archetype
- 10-Level Cap (#18) -- Max level at step 15, accelerated by elites (#63)
- Archetype Spell Tree (#16) -- 3 spells, unlocked at 1/5/10
- Wild Spells as Pure Upside (#37) -- Found spells always positive
- Morality-Flavored Spell Discovery (#74) -- Wild spells match hidden morality
- Unlimited Spells, One Cast Per Turn (#19)
- Equipment: Weapon, Armor, 2 Rings, Collar (#13, #14) -- Primary stat guaranteed + flex stats
- Rarity Tiers (#15) -- Better drops from elites, expensive at shops
- Full Hero Inspection Panel (#53)

**Theme 3: Combat System**
- Turn-Based Actions (#11) -- Attack, Cast Spell, Use Item
- Unified LLM Combat AI (#41) -- Regular=simple, Elite=moderate, Boss=tactical genius
- Structured JSON Combat Interface (#40, #50) -- Action + narration in one call
- Clean Combat Log (#51) -- Player actions mechanical, enemy actions narrated
- Mana Reset Per Combat (#77) -- Fresh Mana each fight, potions for mid-fight recovery
- Persistent HP (#78) -- Damage carries across steps
- Combat-Influenced Morality (#66) -- Fighting style feeds morality
- Finite Consumables (#76) -- Potions are limited resources

**Theme 4: Economy & Merchant System**
- Direct Gold from Combat (#70) -- No junk loot
- Thematic Shop Inventory (#20) -- Shopkeeper type drives stock
- Shop as Tactical Choice (#23) -- One of 3 choices every other step
- Shops as Safe Havens (#68) -- Always reliable, no corruption
- Dynamic LLM-Driven Pricing (#36) -- Prices based on full context
- Pure Buy/Sell (#57) -- No services, no crafting
- Inventory (#71) -- Clean, holds consumables + unequipped gear

**Theme 5: Adventure Structure & Narrative Arc**
- 20 Steps + Boss (#62) -- Fixed adventure length, hidden from player (#54)
- Escalating Danger Curve (#5) -- Low stakes to epic climax
- 3 Choices Per Step Always (#69) -- Fixed structure
- Blind Choices with Clues (#32, #33) -- No event type labels, fair deception
- Villain Established at Start (#10)
- Active Villain Interference (#31) -- Random villain actions during adventure
- Narrative Continuity (#43) -- LLM references earlier events
- Rare Narrative Interrupts (#44, #45) -- Optional dreams/flashbacks, LLM-timed
- Discoverable Boss Weakness (#72) -- Clues woven into narrative
- Permadeath with Restart Options (#29) -- Same adventure or new adventure
- Clean Restart (#75) -- Pure reset, no meta-narrative

**Theme 6: Morality System**
- Hidden Morality Value (#34) -- No visible bar, world tone shifts
- Combat-Influenced Morality (#66) -- Actions in fights matter
- Morality Shapes Boss Encounter (#35) -- Allies, villain dialogue, possible alliance
- Morality-Flavored Spell Discovery (#74) -- Loot matches alignment
- Dynamic Pricing Influenced by Morality (#36) -- NPC attitudes and shop prices

**Theme 7: AI Generation & Technical Architecture**
- Single JSON State Object (#56) -- Entire adventure in browser memory
- Rolling Context Summary (#24) -- Initial setting + compressed choice history
- Aggressive Image Generation (#28) -- Full visual coverage
- Scene Image + 3 Choice Images per Step (#64, #65)
- Speculative Pre-Generation (#26, #27) -- Background generation while player reads
- Claude API for text generation, Image API TBD
- Equipment as Narrative Context (#67) -- Gear referenced in LLM text generation
- Frontend: TypeScript, Backend: API key security layer

**Theme 8: UX & Player Experience**
- 4 Images Per Step (#65) -- Scene + 3 choices
- Scene Description + Image + Choices (#64)
- Skeleton Loading Fallback (#26) -- When pre-gen is outpaced
- No Save, Session-Based (#30) -- Pure browser play
- Single Player Only (#61)

### Breakthrough Concepts

1. **Unified LLM Combat AI with Tiered Intelligence** (#41) -- One system, three intelligence levels. Enemies get smarter as danger escalates.
2. **Blind Choices with Fair Deception** (#32, #33) -- Images and text are gameplay, not decoration. The player reads for clues.
3. **Hidden Morality Coloring Everything** (#34, #35, #74) -- The world silently responds to who the player has become.
4. **Active Villain as Living Antagonist** (#31) -- The boss isn't waiting at the end, they're hunting you throughout.
5. **Discoverable Boss Weakness** (#72) -- Rewards narrative engagement, not just grinding.

### Prioritization Results

**Must-Have (Core Game):** Initialization flow, state management, step loop, combat system, basic events, equipment, merchant system, spell progression, inventory
**Should-Have (Depth):** Villain interference, morality system, boss fight AI, narrative continuity, narrative interrupts
**Nice-to-Have (Polish):** Full image coverage, UI/UX refinement, art style consistency, skeleton loading

## Action Plan

### Phase 1: Core Loop (Playable Prototype)

**1. Landing Page & Initialization**
- Build minimal landing page: seed input (optional), tone slider, art style picker, Begin Adventure button
- All fields optional with sensible defaults
- LLM call: Story + Villain generation (with re-roll)
- LLM call: Hero generation -- name, appearance, archetype, stats (with re-roll)
- LLM call: Spell generation -- 3 archetype spells previewed, first unlocked (with re-roll)
- Assemble style bible from player selections + generated descriptions

**2. State Management**
- Define single JSON state object schema:
  - Hero: stats, level, XP, equipment, inventory, spells, gold
  - Adventure: story setting, villain, morality, context summary, current step
  - Style: art style, tone, hero appearance, villain appearance
- State update functions for all game events
- Rolling context summary generator (compress choices + events after each step)

**3. Step Loop & Choice System**
- 3-choice generation per step with scene description
- Image generation: scene image + 3 choice images (4 per step)
- Pre-generation pipeline: background generation while player engages current step
- Skeleton UI fallback for loading states
- Blind choice routing to event types (combat, treasure, merchant, story)
- Shop as one of 3 choices every other step

**4. Combat System**
- Turn-based combat UI: Attack, Cast Spell, Use Item
- Damage vs Defense calculations
- Spell casting with resource costs (Mana, HP, etc.)
- LLM combat AI via JSON: action + narration for enemy turns
- Tiered intelligence: regular=simple, elite=moderate, boss=tactical genius
- Clean combat log: mechanical player entries, narrated enemy entries
- Mana full reset at combat start, HP persists across steps
- Gold + XP rewards on victory
- Level-up logic with archetype-based stat scaling

**5. Basic Event Types**
- Combat: trigger fight, apply rewards (gold, XP, possible equipment drop)
- Elite Combat: harder fight, better rarity drops, bonus XP
- Treasure: generate loot directly (equipment, consumables, wild spells)
- Story Event: narrative text leading to 3 new choices
- Merchant: shopkeeper with thematic inventory, dynamic pricing, buy/sell

### Phase 2: Economy & Depth

**6. Equipment System**
- 5 slots: Weapon (+Damage + flex), Armor (+Defense + flex), Ring x2 (any stats), Collar (any stats)
- Rarity tiers affecting stat quality
- Equip/unequip from inventory
- Hero inspection panel (stats, gear, spells, gold, inventory, locked spells greyed)

**7. Merchant System**
- Shopkeeper generation: type (alchemist, blacksmith, etc.), personality, inventory based on profession
- Dynamic LLM-driven pricing based on adventure context, morality, progress
- Buy/sell interface
- Shops as reliable safe havens -- no corruption, no villain interference

**8. Spell Progression**
- Archetype spell unlocks at level 5 and level 10
- Wild spell discovery through treasure and magical merchants
- Morality-flavored spell generation (dark path = blood magic, light path = heals)
- All spells accessible in combat, one cast per turn

**9. Inventory Management**
- Consumables: HP potions, Mana potions, temporary buff items
- Finite quantities -- use and they're gone
- Unequipped gear storage
- Clean, meaningful contents only (no junk loot)

### Phase 3: Narrative & Immersion

**10. Villain System**
- Active villain interference events (random, escalating frequency and severity)
- Discoverable boss weakness clues woven into story events, NPC dialogue, treasure
- Villain-themed encounters and environmental effects

**11. Morality System**
- Hidden morality value tracking (no visible bar)
- Influenced by: narrative choices + combat decisions (sparing enemies, dark spells)
- Morality colors: narrative tone, NPC attitudes, shop pricing, spell discovery, visual aesthetic
- Morality-shaped boss encounter: possible allies, unique villain dialogue, alliance offer on dark path

**12. Boss Fight**
- Tactical genius LLM AI with full current-combat context
- Boss has spell kit using same stat-delta system as hero spells
- Discoverable weakness grants advantage (bonus damage, phase skip)
- Boss encounter at step 21 after 20 adventure steps

**13. Narrative Polish**
- Narrative continuity: LLM references earlier events and player choices
- Rare narrative interrupts (dreams, flashbacks, environmental) -- LLM-timed, not guaranteed
- Equipment referenced in narrative descriptions and NPC reactions
- Escalating danger curve expressed through narrative tone and world description

### Phase 4: Polish & UX

**14. Death & Restart**
- Game over screen: restart same adventure (level 1, clean reset) or generate new adventure
- No meta-narrative on restart, pure fresh start

**15. Image Generation Polish**
- Style bible consistency across all image calls
- Hero portrait, enemy portraits, shopkeeper portraits, NPC portraits
- Scene images + choice preview images (4 per step)
- Art style presets applied consistently

**16. UI/UX Design**
- Full UI/UX design pass (dedicated design phase)
- Combat UI, shop UI, inventory UI, choice presentation
- Skeleton loading states for pre-generation gaps
- Responsive design considerations

### Technical Decisions

| Decision | Choice |
|----------|--------|
| Language | TypeScript |
| Architecture | Frontend + Backend (API key security) |
| Text Generation | Claude API |
| Image Generation | TBD |
| State Management | Single JSON object, client-side |
| Persistence | None -- session-based, browser memory |
| Multiplayer | No -- single player only |

## Session Summary and Insights

### Key Achievements

- **78 ideas** generated across 3 techniques (Morphological Analysis, What If Scenarios, SCAMPER)
- **8 thematic clusters** covering every major game system
- **5 breakthrough concepts** that define the game's unique identity
- **4-phase action plan** from prototype to polish
- **Complete game design** covering initialization, combat, economy, narrative, morality, and technical architecture

### Core Game Identity

This is an **AI-powered single-player browser RPG** where the LLM serves as dungeon master, artist, narrator, and enemy intelligence simultaneously. What makes it special:

1. **Every playthrough is unique** -- seed phrase + LLM generation = infinite adventures
2. **Choices are gameplay** -- blind choices with visual/text clues make decision-making a skill
3. **The villain is alive** -- active interference throughout, not just a final boss
4. **Your identity emerges** -- hidden morality shapes the world around your playstyle
5. **Combat intelligence scales** -- enemies get smarter, not just stronger
6. **Full visual immersion** -- every moment illustrated through AI-generated art

### Game Design Summary

- **Adventure:** 20 steps + boss fight, hidden progress, escalating danger
- **Initialization:** Optional seed + tone slider + art style → Story+Villain → Hero → Spells (re-rollable)
- **Steps:** Scene description + scene image + 3 blind choices with images
- **Events:** Combat, Elite Combat, Treasure, Merchant (every other step), Story Fork
- **Combat:** Turn-based (Attack/Cast/Item), LLM-driven enemy AI (tiered intelligence), JSON interface
- **Hero:** Archetype-driven stats (HP/Mana/Defense/Damage), 10 levels, 3 archetype spells (1/5/10), wild spells
- **Equipment:** Weapon, Armor, 2 Rings, Collar -- rarity tiers, primary + flex stats
- **Economy:** Gold from combat, dynamic LLM pricing, thematic shops, buy/sell only
- **Resources:** HP persists across steps, Mana resets per combat, finite consumables
- **Morality:** Hidden value, influences narrative/NPCs/shops/spells/boss encounter
- **Villain:** Established at start, active interference, discoverable weakness
- **Death:** Permadeath, restart same adventure or new adventure, clean reset
- **Tech:** TypeScript, Claude API, Frontend + Backend, single JSON state, pre-generation pipeline
