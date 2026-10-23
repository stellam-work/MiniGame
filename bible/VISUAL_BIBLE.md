# Mini-Game Studio - Visual & Interaction Bible

**Version:** 1.0  
**Status:** Approved baseline for the shared mini-game collection  
**Typography:** Fraunces + Nunito Sans  
**Maintainer:** Game Studio owner  
**Applies to:** Every game, sample scene, UI component, generated illustration, animation, and promotional preview produced by the Mini-Game Studio Agent.

> **North star:** An illustrated narrative world made from elegant, expressive shapes. Environments are layered and painterly; people are simplified yet unmistakably individual. Colour is warm and controlled, movement is subtle, and interface chrome never competes with the story.

This bible defines the **shared identity**, not a fixed historical period, set of characters, landscape, or gameplay mechanic. Each game may have its own tone, setting, accent colours, and interaction model while remaining recognisably part of the same collection.

## 1. Reference interpretation and originality

The supplied visual references include scenes from *Old Man's Journey* and three examples of simplified contemporary character illustration. They establish a **direction**, not artwork to reproduce. The visual characteristics to retain are:

- Narrative compositions with strong silhouettes and an illustrated rather than photographic sense of place.
- Rolling and overlapping large forms; architecture and vegetation built from simplified colour masses.
- Hand-crafted tonal modulation and a quiet, lightly textured surface.
- Recognisable, expressive human figures with economical facial and clothing detail.
- Occasional graphic reflections and layered atmospheric depth.

**Do not** copy a reference image's composition, characters, unique buildings, logos, text, or proprietary game imagery. Do not instruct image models to duplicate named artworks frame for frame. Generate original scenes from the visual grammar described below. The owner's reference uploads can be kept privately under `bible/references/` if rights and repository visibility permit; this Markdown file does not depend on those assets being present.

## 2. Visual hierarchy: environments and characters

Two related but distinct rendering treatments coexist:

| Layer | Treatment | Priority |
| --- | --- | --- |
| Landscape and architecture | Soft-edged, painterly cut-paper forms; simplified planar light; restrained surface grain | Atmosphere and spatial storytelling |
| People and animals | Cleaner colour-block illustration; distinguishable silhouette, face, hairstyle, costume and gesture | Individual identity and emotion |
| Important objects | Graphic, recognisable shapes with slightly firmer edges and intentional contrast | Touch discoverability |
| UI | Quiet, flat/soft-edged components using shared colour and type tokens | Clarity without breaking immersion |

**Characters are not faceless icons.** Give each recurring figure identifiable facial features, hair or headwear, clothing silhouette, posture, and a distinctive colour balance. Simplification should reduce unhelpful detail, not remove identity.

## 3. Shape language

### Organic forms

- Build trees, hills, bushes, clouds, flowers, and rocks from a few large, slightly irregular masses.
- Prefer flowing, rounded contours and intentional asymmetry; avoid perfectly repeated circles or uniform blobs.
- Layer foliage into recognisable silhouettes with 2-4 subordinate shapes, rather than hundreds of tiny leaves.
- Use shape overlap and irregular negative space to make scenery feel constructed by hand.

### Architecture and props

- Reduce objects to their most recognisable geometry: broad wall planes, pitched roofs, window rhythms, handles, tools, and furnishings.
- Straight architectural lines are welcome; keep them visually softened by slight hand-drawn variation and painterly tonal treatment.
- Minimise tiny decoration. Detail should explain setting, historical use, or interaction.

### Characters

- Use mildly stylised but credible human proportions; not chibi, bobble-head, superhero, or highly anatomical rendering.
- Keep silhouettes legible at small on-screen size. Identify important poses before drawing internal detail.
- Represent faces with a limited set of purposeful features: brows, eyes, nose, mouth, hair, glasses, beard, etc., as appropriate.
- Convey emotion through face, shoulders, hands, direction of gaze, and placement in the scene.
- Clothing should show a few meaningful folds and 2-4 tonal/colour planes per material, not complex cloth simulation.
- For a character sheet, maintain consistent proportions, costume construction, palette, and facial identity across poses.

## 4. Line work, edges and shading

- **No universal black contour.** Separate forms mainly through adjacent colour values, overlaps, and shape boundaries.
- Use fine lines selectively for faces, glasses, seams, branches, or small props. Prefer coloured lines derived from the object's shade.
- Organic edges can be softly irregular; interaction-critical items may be a little crisper.
- Model objects with broad light/dark colour planes. A character jacket, for example, may have a base fill, light-facing fill, cast-shadow fill, and occasional detail tone.
- Avoid heavy gradients, plastic airbrushing, realism-driven normal maps, glossy bevels, and harsh cartoon cel-shading.
- Keep most shadows chromatic and soft-edged, with intentional painted shapes rather than physically perfect simulations.
- Avoid indiscriminate blur: shapes should remain readable, even when the atmosphere is gentle.

## 5. Texture and surface finish

**Default texture strength: subtle.** The cleanness of the more recent character references is as important as the atmosphere of the landscape references.

- Allow a very low-amplitude paper/grain texture on scenery and selected surfaces to remove sterile digital smoothness.
- Apply grain consistently within a scene; do not mix very rough paper with glossy vectors.
- Characters can be almost texture-free, with texture concentrated in landscapes, stone, timber, foliage, and large colour planes.
- Typography, button text, icons, and small details must remain sharp. Never place noise over text.
- Prefer diffuse, matte materials. Reserve brighter highlights for deliberate narrative emphasis.

## 6. Light, tonality, shadows and atmosphere

- Default mood: muted, warm or softly cool, humane and cinematic. The palette can become darker, quieter, or more tense to serve the story.
- Lighting is often diffuse, with early/late-day warmth, overcast softness, or gentle practical interior light.
- Keep scene contrast moderate overall, **but preserve sufficient local contrast** between focal objects and background.
- Build depth by progressively reducing detail, contrast, and saturation in distant layers.
- Strong directional light and deep shadow are permitted for specific dramatic beats, but should still be described in illustrated colour planes rather than photorealistic effects.
- Do not automatically make every story cheerful, pastoral, or sunlit; mood belongs to each game's narrative.

## 7. Reflections and highlights

Reflections are stylised graphic devices, not a realistic renderer's output.

- For still water, use a simplified vertically mirrored silhouette where helpful, lowered in opacity or contrast and partly interrupted by horizontal bands, ripples, or broad transparent planes.
- Reflection geometry may be incomplete; readability and mood matter more than exact perspective.
- Glass can use one translucent shape and a few soft highlight strokes.
- Polished metal may have a small muted highlight; avoid high-gloss white streaks and exaggerated lens effects.
- No mandatory reflections: include them only when they support the scene.

## 8. Layering, depth and camera

**Camera freedom:** side-on, elevated, and faux-isometric illustrated compositions are all acceptable. Select the perspective that best supports the approved mechanic and story.

Build scenes as independently reusable visual layers when movement or interactivity needs them:

1. Far atmosphere / sky.
2. Distant terrain or architectural silhouette.
3. Midground environment.
4. Actor and playable objects.
5. Near foreground framing elements.
6. Optional weather, light, and other subtle overlays.
7. Screen-space interface, outside the illustrated world when necessary.

Rules:

- Use overlap, size changes, reduced contrast, and soft atmospheric recession to indicate distance.
- Parallax should be restrained; do not make the scenery slide more prominently than the action.
- Foreground branches, rails, window frames, or vegetation may provide intimacy, but should not hide interactive targets.
- A story may use a single full illustration instead of parallax if that is the more elegant or robust solution.
- For responsive layouts, preserve compositional focus and crop/reframe rather than stretching artwork.
- Plan safe areas for captions and controls. Do not place important detail near the edges of variable-ratio screens.

## 9. Colour system

### 9.1 Permanent core palette

The following eight owner-supplied hex values are authoritative and **must remain exact** in the design tokens.

| Token | Hex | Design role |
| --- | --- | --- |
| `sage` | `#8FB474` | Vegetation, gentle positive/active surfaces, secondary landscape plane |
| `dusty-aqua` | `#74C3C3` | Water, cool environmental planes, calm interactive secondary accent |
| `forest` | `#30552B` | Deep foliage, dark scene anchors, headings, important UI outlines and dark buttons |
| `terracotta` | `#C75E18` | Warm earth, architectural details, selected calls to action or key props |
| `mist` | `#C5D6C6` | Airy grey-green backgrounds, distant landscape, softened neutral panels |
| `olive-cream` | `#DEE0B4` | Muted sunlight, secondary light backgrounds, atmospheric transitions |
| `sand` | `#FAE2C5` | Warm surfaces, walls, story/dialogue cards, neutral areas |
| `ivory` | `#FAF1E6` | Main light canvas, light text on dark surfaces, quiet UI backgrounds |

```css
:root {
  --color-sage: #8FB474;
  --color-dusty-aqua: #74C3C3;
  --color-forest: #30552B;
  --color-terracotta: #C75E18;
  --color-mist: #C5D6C6;
  --color-olive-cream: #DEE0B4;
  --color-sand: #FAE2C5;
  --color-ivory: #FAF1E6;
}
```

### 9.2 Palette rules

- Use the core colours as the collection's shared identity, especially for base surfaces, landscape families, typography, and UI chrome.
- Do **not** force every object in every historical or narrative setting into one of eight hex values. Derive nearby tints/shades and culturally or historically appropriate material colours as needed.
- Give each game a clearly documented **accent palette** (usually 2-4 hues, plus their lighter/darker states), selected for the story. Accents are subordinate to the stable core, not a second competing visual system.
- Use strong accent colours sparingly on narratively significant items or outcomes. Avoid neon, saturated primary colours, and arbitrary status rainbow coding.
- Avoid pure black or pure white as dominant fills; near-black accents and clean whites are allowed where function or lighting needs them.
- Design text/surface combinations for readability; do not use light sage on ivory for small body copy. Prefer `forest` on `ivory`/`sand` and `ivory` on `forest` for high-salience UI.
- Express uncertain, difficult, or tense scenes through **relative darkness, desaturation, and selective contrast**, not through a new UI brand.

### 9.3 Accent palette contract per game

Every game brief must declare:

```yaml
visual_palette:
  core: shared-bible-v1
  accent_name: "<narrative purpose>"
  accents:
    primary: "#......"
    secondary: "#......"
    emphasis: "#......"
  usage: "Explain exactly which characters/objects/moments use these colours."
  mood_variants: ["normal", "dramatic-if-needed"]
```

Accent colours are proposed during discovery and approved **once**, with the complete creative package.

## 10. Typography: locked pairing

**Display and chapter/title typography:** **Fraunces**.  
**Dialogue, instructions, menus, buttons, UI labels, and body text:** **Nunito Sans**.

- Fraunces is for narrative character, not for long dialogue paragraphs or dense help screens.
- Nunito Sans carries routine interaction text, with friendly rounded forms and readable distinction at touch-screen sizes.
- Suggested initial hierarchy (tune by device and game): scene title 30-48 CSS px Fraunces; dialogue 20-26 px Nunito Sans; UI button 18-22 px Nunito Sans; secondary labels 16-18 px Nunito Sans.
- Preserve sufficient line height, especially for French, German, and Dutch text expansion. Avoid embedding narrative text inside raster images.
- Bundle legitimately obtained, appropriately licensed font assets locally in the **game build** and keep licence notices. Do not depend on a live font CDN for runtime. The bible Markdown package does not distribute font binaries.
- Verify actual glyph coverage per language and provide a compatible local fallback if needed.
- Use at most a few intentional weight variations; avoid mixing additional decorative fonts without an explicit bible revision.

## 11. Interface and touch interactions

The UI is a quiet part of the story world, not a separate high-tech dashboard.

- Use generous negative space, matte fills, softly rounded geometry, minimal borders, and gentle shadows.
- Prefer `sand`/`ivory` for dialogue and secondary overlays, with `forest` type. A prominent active control may use `forest` with `ivory` text.
- Use a consistent family of icons, preferably simple filled or softly stroked motifs, avoiding hyper-thin touch targets.
- Make primary touch targets comfortably finger-sized (baseline around 44-48 CSS px or larger, adjusted for the device).
- Every essential action must work equivalently with tap and primary mouse click. Drag interactions must work with touch/pointer events, not hover.
- If visual hover states exist on desktop, they are purely supplemental. The game never requires hover, right-click, keyboard shortcuts, or precision cursor placement.
- Use clear visual feedback for pressed, selected, dragged, accepted, rejected, or inactive actions, while maintaining the illustrated aesthetic.
- Language selection and restart controls must be discoverable but unobtrusive.
- Place interactive hit zones independently of tiny decorative silhouettes so they remain usable on iPad-sized screens.

## 12. Animation and transitions

- Default motion is restrained: mild idle gestures, foliage sway, slow atmospheric movement, paper-like scene transitions, and small reactive object movement.
- Use easing that feels organic, not elastic or arcade-like, unless a specific game mechanic demands speed.
- Prefer transforming scene layers and character parts rather than animating photographic frames.
- A dramatic game may legitimately have fast interactions, but the interface should not introduce gratuitous motion.
- Keep narrative state visually comprehensible during transitions; the player's choice and consequence must remain legible.
- For each animation, define **trigger**, **affected layer**, **duration**, **end state**, and **interrupt/reset behaviour**.

## 13. Asset-generation and export contract

### Sample art required for the first approval package

Produce at least **one original illustrated sample asset** and **two sample scenes** (e.g., opening tableau and core interaction / consequence). If an image-generation tool is unavailable, do not pretend a generated asset exists: produce a faithful visual-specification sheet or an original SVG mock-up and label it honestly. The user may reject or replace an image through Higgsfield.

### Asset prompts must specify

1. Story situation, period and setting.
2. Main focal subject and composition.
3. Camera viewpoint and aspect ratio.
4. Shape and character treatment drawn from this bible.
5. Named core colours plus approved game accents.
6. Light, painterly shadow, subtle grain and intended mood.
7. Layer separation / transparent background requirements.
8. What must **not** appear (photorealism, hard outlines, plastic highlights, crowded detailing, borrowed game imagery, rendered UI text, etc.).

**Reusable positive prompt:**

> Original illustrated narrative game artwork. Simplified rounded and gently irregular shapes; harmonious colour-block characters with recognisable expressions and costume identity; layered landscape or architecture with soft painted tonal planes, almost invisible matte grain, muted atmospheric depth, restrained reflections and highlights, and deliberate negative space. Core tones from sage `#8FB474`, dusty aqua `#74C3C3`, forest `#30552B`, terracotta `#C75E18`, mist `#C5D6C6`, olive cream `#DEE0B4`, sand `#FAE2C5`, and ivory `#FAF1E6`; apply the approved story-specific accents. Clear foreground/midground/background separation. Original composition designed for an iPad-sized interactive scene.

**Reusable negative prompt / quality guardrails:**

> No photorealism, 3D-plastic shading, glossy specular materials, ink-heavy cartoon outlines, pixel art, anime conventions, neon palette, photographic textures, excessive lens blur, realistic rendering noise, cluttered micro-detail, warped anatomy, embedded dialogue text, copied scenes or characters, or logos from existing games.

### Technical export principles

- Keep originals/master sources when generated or edited. Export runtime-optimised assets separately.
- Prefer transparent PNG/WebP for isolated characters/props and well-compressed web imagery for scene panels; SVG is acceptable for deliberately authored scalable interface art.
- Match layer dimensions, crop, visual anchor, pivot, and colour treatment so they compose without manual nudging.
- Use an asset manifest mapping stable IDs to files, expected dimensions, anchor points, semantic roles, and attribution/licence status.
- Give the user an easy **Higgsfield replacement path**: replace files by ID (or update a manifest), preserve transparent backgrounds and anchors, rerun the build; never bury asset filenames in many source files.
- Never fetch production-critical graphics from a runtime network API.

Suggested filenames: `scene-01-bg.webp`, `scene-01-midground.webp`, `character-guide-idle.png`, `prop-letter-closed.png`, `prop-letter-open.png`. Add language suffixes only to assets that truly contain localised visual text; prefer text rendering in code.

## 14. Story-specific flexibility and approval

These are **fixed**: overall illustrated-narrative aesthetic, subtle texture, simplified identifiable characters, coherent layered compositions, permanent eight-colour core, Fraunces + Nunito Sans, integrated UI, touch/mouse parity.

These are **variable per game**: story, historical period, age group, genre, emotional tempo, game mechanic, camera type, accent palette, character identities, screen orientation, sound, narrative duration, and number of endings.

The game agent may choose mechanics freely. It should change mechanics to **improve the story** while preserving the user's concept and intended meaning. It must obtain the user's single consolidated approval for the complete brief, mechanics, and sample scenes before building the full game.

## 15. Visual review rubric

Use this checklist when preparing the approval package and reviewing rendered scenes. It is a **design conformance check**, not a demand for separate usability or performance studies.

- [ ] Clearly original artwork, not a near-copy of any reference composition or character.
- [ ] Rounded/irregular, economical shapes; no unnecessary outlines.
- [ ] Environment feels layered; focal objects and interactive targets are unmistakable.
- [ ] Characters retain unique identity and readable emotion at game scale.
- [ ] Surface grain is subtle, not noisy; text and icons stay sharp.
- [ ] Shading uses purposeful colour planes; reflections are stylised and restrained.
- [ ] Core eight hex tokens are unchanged; story accent colours are documented.
- [ ] Fraunces and Nunito Sans are assigned to their intended roles.
- [ ] The composition works in the approved iPad orientation/aspect and adapts without distortion.
- [ ] The illustrations and UI support the narrative instead of distracting from it.

## 16. Change control

- This document is the **source of truth** for common visual rules.
- Project briefs may override variable rules, never fixed rules without an explicit bible version change.
- Record any approved exception in the game's brief (`visual_exceptions`) with reason and scope.
- Keep an entry in `LESSONS.md` for reusable insights. A lesson is **not** a bible revision until the owner explicitly accepts the proposed change.
- Version the bible deliberately (`1.0`, `1.1`, `2.0`); note which version each game targets.

### External implementation references (optional reading)

- Fraunces / Nunito Sans source and licence information: https://github.com/google/fonts
- Browser display mode guidance: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Manifest/Reference/display

---
**End of Visual Bible v1.0**