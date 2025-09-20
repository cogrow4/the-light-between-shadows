# Development Roadmap - The Light Between Shadows
## Simplified Development Approach for Solo Developer

### 🎯 Project Scope Philosophy
**Goal:** Create a beautiful, meaningful narrative experience that's achievable for a solo developer
**Timeline:** 12-18 months part-time development
**Focus:** Quality over quantity, emotional impact over technical complexity

## Phase 1: Foundation (Months 1-3)
### Core Systems - Keep It Simple

#### 1.1 Basic Godot Setup
- **Week 1-2:** Project setup, basic scene structure
- **Week 3-4:** Simple 2.5D character controller (walk, interact)
- **Week 5-6:** Basic UI system (menus, settings)
- **Week 7-8:** Save/load system using Godot's built-in resources
- **Week 9-12:** Simple document reading system

**Deliverable:** Playable prototype with Eilidh walking around and reading documents

#### 1.2 Art Pipeline (Simplified)
- **Focus:** 2D sprites with parallax backgrounds (much easier than 3D)
- **Character:** Simple 2D sprite with basic animations (walk, idle, examine)
- **Environments:** Layered 2D backgrounds with foreground interaction objects
- **UI:** Clean, simple interface design
- **Tools:** Use free/affordable tools like Krita, GIMP, or Procreate

**Key Simplification:** No complex 3D modeling - stick to 2D art with depth illusion

## Phase 2: Core Gameplay (Months 4-6)
### Essential Mechanics Only

#### 2.1 Investigation System (Simplified)
- **Document System:** Simple text files with basic formatting
- **Clue Tracking:** Basic checklist system, no complex pattern matching
- **Journal:** Simple text entries with optional sketches
- **Progress Gates:** Linear progression with clear requirements

**Implementation:** Use Godot's Resource system for documents, simple boolean flags for progress

#### 2.2 Basic Environments
- **3-4 Main Areas:** Surface Scáthghlenn, Archives, Deep Chamber, Observatory
- **Simple Layouts:** Each area is a single scene with multiple rooms/sections
- **Interaction Objects:** Click to examine, simple text descriptions
- **No Complex Puzzles:** Focus on discovery and reading, not puzzle-solving

**Key Simplification:** Pre-rendered backgrounds with simple interaction hotspots

## Phase 3: Content Creation (Months 7-10)
### Story Implementation

#### 3.1 Narrative Content
- **Documents:** 50-100 readable documents (manageable scope)
- **Environmental Storytelling:** Visual clues in backgrounds
- **Eilidh's Thoughts:** Simple text-based internal monologue
- **Linear Story:** Clear progression path, minimal branching

#### 3.2 Art Assets (Realistic Scope)
- **Character Sprites:** 4-6 basic animations
- **Backgrounds:** 15-20 painted backgrounds with parallax layers
- **UI Elements:** Simple, clean interface graphics
- **Effects:** Basic particle effects for nanite abilities

**Time-Saving Approach:** Use photo references and digital painting techniques

## Phase 4: Polish and Audio (Months 11-12)
### Final Implementation

#### 4.1 Audio (Keep Simple)
- **Music:** 5-8 ambient tracks (can use royalty-free with attribution)
- **Sound Effects:** Basic interaction sounds, footsteps, ambient
- **Voice:** Optional - could be text-only to save time and budget
- **Implementation:** Godot's built-in audio system

#### 4.2 Final Polish
- **Bug Testing:** Focus on core functionality
- **Performance:** Optimize for smooth 60fps
- **Accessibility:** Basic options (text size, volume controls)
- **Platform Testing:** Windows/Mac/Linux builds

## Simplified Technical Approach

### 🛠️ Technology Choices for Ease of Development

#### Game Engine: Godot 4.x
**Why Godot:**
- Free and open-source
- Excellent 2D capabilities
- GDScript is Python-like (easy to learn)
- Great documentation and community
- Built-in save system and resource management
- Cross-platform export

#### Art Style: 2D with Parallax (Not 3D)
**Simplified Approach:**
- Hand-painted 2D backgrounds
- 2D character sprites
- Parallax scrolling for depth
- Simple particle effects
- UI overlays for interaction

#### Programming Approach
**Keep Code Simple:**
- Use Godot's scene system for modular design
- Signals for event handling
- Resources for data storage
- Minimal custom classes
- Comment everything for future reference

### 📊 Realistic Asset Requirements

#### Art Assets (Manageable Scope)
- **Character Sprites:** 1 character, 6 animations = ~30 frames
- **Backgrounds:** 20 scenes × 3 layers = 60 background elements
- **UI Graphics:** 20-30 interface elements
- **Effects:** 10-15 simple particle textures

#### Audio Assets (Minimal Viable)
- **Music Tracks:** 6-8 ambient pieces (3-5 minutes each)
- **Sound Effects:** 30-50 interaction and ambient sounds
- **Voice Acting:** Optional (can launch without, add later)

#### Text Content
- **Documents:** 50-100 readable items
- **UI Text:** Menus, tooltips, system messages
- **Narrative Text:** Eilidh's thoughts and observations

### 🎮 Simplified Game Features

#### Core Features (Must Have)
- Walk around 2D environments
- Click to examine objects and read documents
- Simple inventory/journal system
- Linear story progression
- Save/load functionality
- Basic settings menu

#### Nice-to-Have Features (If Time Permits)
- Simple nanite ability effects
- Background animation
- Ambient sound layers
- Screenshot mode
- Achievement system

#### Features to Skip (For Now)
- Complex puzzle mechanics
- Multiple endings
- Voice acting
- 3D graphics
- Multiplayer features
- Advanced AI systems

### 💡 Development Tips for Success

#### Time Management
- **Set Weekly Goals:** Small, achievable milestones
- **Prototype First:** Test ideas quickly before full implementation
- **Use Placeholders:** Gray boxes and stick figures until art is ready
- **Regular Builds:** Test on target platforms frequently

#### Asset Creation Efficiency
- **Reuse Elements:** Create modular art pieces
- **Simple Color Palettes:** Limit colors for consistency
- **Template Systems:** Create templates for documents and UI
- **Reference Photos:** Use real-world references for backgrounds

#### Scope Management
- **Feature Creep Prevention:** Write down ideas but don't implement immediately
- **MVP First:** Get the minimum viable product working
- **Polish Later:** Focus on functionality before visual polish
- **Player Testing:** Get feedback early and often

### 🚀 Launch Strategy

#### Minimum Viable Product
- **Core Story:** Complete narrative experience
- **Basic Functionality:** All essential features working
- **Single Platform:** Launch on PC first
- **Essential Polish:** No game-breaking bugs

#### Post-Launch Improvements
- **Additional Platforms:** Mac/Linux versions
- **Quality of Life:** Based on player feedback
- **Content Updates:** Additional documents or areas
- **Community Features:** Screenshot sharing, etc.

### 📈 Success Metrics (Realistic)

#### Development Success
- **Completion:** Finished game in 12-18 months
- **Quality:** Stable, bug-free experience
- **Story:** Complete narrative arc
- **Art:** Consistent visual style

#### Launch Success
- **Player Completion:** 60%+ finish the story
- **Reviews:** Positive feedback on narrative and atmosphere
- **Technical:** Smooth performance on target hardware
- **Personal:** Satisfaction with completed project

---

## 🎯 Key Takeaways for Manageable Development

1. **2D is Much Easier:** Stick to 2D art with parallax for depth
2. **Linear is Fine:** Don't overcomplicate with branching narratives
3. **Text-Heavy is OK:** Rich text content is cheaper than voice acting
4. **Godot is Perfect:** Excellent for 2D indie games
5. **Scope Small:** Better to have a polished short game than an unfinished epic
6. **Iterate Quickly:** Get something playable early and improve it
7. **Use Your Strengths:** Focus on storytelling and atmosphere over complex mechanics

**Remember:** The goal is to create a beautiful, meaningful experience that tells Eilidh's story effectively. Technical complexity should serve the narrative, not overshadow it.
