# Generation record

Mode: previously authorized ImageGen CLI fallback; model gpt-image-2.
Final resampling: nearest neighbor, with common body scale and baseline.


## base

Image 1 is the authoritative sprite master, enlarged 16x using nearest-neighbor from the official Terraria Guide 26x46 source. Preserve this image's character EXACTLY, including every coarse square pixel cluster, skinny silhouette, head-to-body ratio, clothing color, hair shape, and tiny eye. Reproduce this same centered full-body sprite on the same uniform pure #FF00FF background, at the same scale and position. This is sprite preservation, not character redesign or illustration. The desired deliverable looks like the original game sprite enlarged, with no added details. Do not make him cute, chibi, round, muscular, broad, or big-headed. Do not add eye whites, iris, facial detail, dithering, smooth shading, or extra hair strands. Every visible square is a native pixel and must remain a large hard square, not many tiny pixels. No new colors or texture. Images 2 and 3 confirm the original low-resolution source; image 4 confirms game appearance only. Ignore scene background. One character only. All background pixels flat #FF00FF. Keep the pose and all proportions in Image 1.


## idle

Create one horizontal animation strip for Codex pet `terraria-guide`, state `idle`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Calm low-distraction resting loop: subtle breathing, tiny blink, slight head/body bob, and only quiet persona-preserving motion.

State requirements:
- CRITICAL: idle is the low-distraction baseline state and the first frame is also used as the reduced-motion static pet.
- Use only subtle idle motion: gentle breathing, a tiny blink, a slight head or body bob, a very small material sway, or another quiet motion that fits the pet persona.
- Keep the pet essentially in the same pose, facing direction, silhouette, markings, palette, and prop state across all 6 frames.
- Idle variation must stay calm but still read as animation; do not repeat effectively identical copies across the loop.
- Do not show waving, walking, running, jumping, talking, working, reviewing, emotional reactions, large gestures, item interactions, or new props.
- Feet, base, body, or object anchor should remain planted or nearly planted.
- The first and last frames should be very close visually so the loop feels calm and does not pop.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running-right

Create one horizontal animation strip for Codex pet `terraria-guide`, state `running-right`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-right loop: show directional movement to the right through body and limb poses only.

State requirements:
- Show directional drag movement to the right through body, limb, and prop movement only.
- The row must unmistakably face and travel right.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running-left

Create one horizontal animation strip for Codex pet `terraria-guide`, state `running-left`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Dragging-left loop: show directional movement to the left through body and limb poses only.

State requirements:
- Show directional drag movement to the left through body, limb, and prop movement only.
- The row must unmistakably face and travel left.
- The movement cadence must alternate visibly across the 8 frames instead of repeating one nearly static stride.
- Do not draw speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## waving

Create one horizontal animation strip for Codex pet `terraria-guide`, state `waving`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 4 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 4 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Greeting loop: paw or limb down, raised, tilted, and returning in a friendly attention gesture.

State requirements:
- Show the greeting through paw, hand, wing, or limb pose only.
- Do not draw wave marks, motion arcs, lines, sparkles, symbols, or floating effects around the gesture.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## jumping

Create one horizontal animation strip for Codex pet `terraria-guide`, state `jumping`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 5 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 5 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Hover jump loop: anticipation, lift, airborne peak, descent, and settle through body height.

State requirements:
- Show the jump through pose and vertical body position only: anticipation, lift, airborne peak, descent, settle.
- Do not draw ground shadows, contact shadows, drop shadows, oval shadows, landing marks, dust, smears, bounce pads, or motion marks under the pet.
- Keep the background outside the pet perfectly flat chroma key with no darker key-colored patches.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## failed

Create one horizontal animation strip for Codex pet `terraria-guide`, state `failed`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 8 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 8 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Blocked/failed loop: slumped or deflated reaction with sad or closed eyes.

State requirements:
- Show failure through slumped pose, drooping ears/limbs, closed or sad eyes, and lower body position.
- Tears, small smoke puffs, or tiny stars are allowed only if attached to or overlapping the pet silhouette and kept inside the same frame slot.
- Do not draw red X marks, floating symbols, detached stars, separated smoke clouds, falling tear drops, dust, or other loose effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## waiting

Create one horizontal animation strip for Codex pet `terraria-guide`, state `waiting`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Needs-input loop: expectant asking pose for approval, help, or user input.

State requirements:
- Show that Codex needs approval, help, or user input through an expectant asking pose.
- Keep the motion patient and readable, without turning it into ordinary idle or review.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## running

Create one horizontal animation strip for Codex pet `terraria-guide`, state `running`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Working loop: focused active-task processing, thinking, typing, scanning, or effortful concentration; not literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, or directional travel.

State requirements:
- Show the pet actively working or processing, as if running a task: focused posture, busy hands or paws, purposeful bobbing, thinking motion, tool or prop motion only if already part of the pet identity, or other non-locomotion activity.
- Do not show literal foot-running, jogging, sprinting, treadmill motion, raised knees, long steps, pumping arms, directional travel, speed lines, dust clouds, floor shadows, motion trails, or detached motion effects.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## review

Create one horizontal animation strip for Codex pet `terraria-guide`, state `review`.

Use the attached canonical base for identity. Use the attached layout guide only for slot count, spacing, centering, and padding; do not draw the guide.

Output exactly 6 full-body frames in one left-to-right row on flat pure user-selected #FF00FF. Treat the row as 6 invisible equal-width slots: one centered complete pose per slot, evenly spaced, with no overlap, clipping, empty slots, labels, or borders.

Identity: same pet in every frame: Guide NPC exact identity from official image. Side-view game sprite with small natural pixel motions. Preserve native pixel economy and proportions across every action. All reference images are style/identity references only; no background scenery.. Preserve silhouette, face, proportions, markings, palette, material, style, and props.
Style: Pet-safe sprite: compact full-body mascot, readable in a 192x208 cell, clear silhouette, simple face, stable palette/materials, and crisp edges for chroma-key extraction. Style `pixel`: Native-resolution Terraria sprite faithfully matching official Guide.png, approximately 26x46 effective pixels, hard square clusters, small head and narrow upright body. User style notes: Strict Terraria native-resolution pixel sprite. Effective 26x46 pixel silhouette, small head, narrow straight torso, block limbs, sparse tiny eyes, grey sage shirt, dark navy trousers. Large square pixel clusters and hard stepped edges, 2-3 flat shades per material. No Stardew Valley portrait styling, no chibi anatomy, no gradients, no antialiasing, no big eyes..
Animation continuity: keep apparent pet scale and baseline stable within the row unless the state itself intentionally changes vertical position, such as `jumping`. Move the pose within the slot instead of redrawing the pet larger or smaller frame to frame.

State action: Ready-review loop: focused inspection of completed output with lean, blink, narrowed eyes, head tilt, or paw pose.

State requirements:
- Show review through lean, blink, narrowed eyes, head tilt, or paw/hand position.
- Do not add magnifying glasses, papers, code, UI, punctuation, symbols, or other new props unless they already exist in the base pet identity.

Clean extraction: crisp opaque edges, safe padding, no scenery, text, guide marks, checkerboard, shadows, glows, motion blur, speed lines, dust, detached effects, stray pixels, or chroma-key colors inside the pet.


## look-cardinals

Create one horizontal four-cardinal anchor strip for Codex pet `terraria-guide`.

Use the attached canonical base, completed standard contact sheet, and layout guide for exact identity, style, scale, baseline, face construction, materials, palette, markings, props, and spacing. Read `qa/look-mechanics.md` and use the pet's natural gaze mechanism.

Output exactly four centered complete full-body poses in this exact left-to-right order: `000 up`, `090 screen-right`, `180 down`, `270 screen-left`. Screen-left and screen-right always mean the viewer's image edges, never the character's own left or right.

For `000`, keep the face broadly frontal and point the eyes and natural head mechanism toward the TOP edge. For `090`, put the nose tip, pupils, face surface, or natural aiming feature on the screen-right side of the head center. For `180`, keep the face broadly frontal and point toward the BOTTOM edge. For `270`, apply the inverse screen-left landmark rule. Every cardinal must be unmistakable without labels.

Place one pose in each invisible equal-width slot on a flat pure user-selected #FF00FF background with generous padding. Keep scale, feet/base, lower body, and registration consistent across all four slots.

Do not rotate, skew, or tilt the whole sprite to fake gaze. Do not add replacement eyes, labels, degree text, arrows, boxes, guide marks, shadows, scenery, detached effects, or chroma-key colors inside the pet.
# Terraria Guide look mechanics

The source is a coarse 26x46-style human sprite. Preserve the official hair envelope, grey-sage shirt, dark trousers and original tiny white/dark eye pixels. Do not enlarge the face or add anime eyes to express gaze.

Feet, trousers and lower torso stay anchored at a common baseline. Head/neck yaw and pitch lead attention, with minimal upper-shoulder follow-through. Redraw the original few eye/eyelid pixels within the face, alongside the head angle; no sliding replacement eyes and no full-sprite rotation. Limbs stay quiet, no props.

000: head lifted, chin/nose and eye line clearly aimed up, face more visible under the hair. Horizontal attention centered. 090: clear screen-right profile; nose and original eye on right side of head. 180: head bowed, nose/eye line aimed below, more hair crown visible and face partly occluded. Horizontal attention centered. 270: clear screen-left profile; nose and eye on left side. This must visibly oppose 090.

Intermediates follow one clockwise arc up -> right -> down -> left -> up. Each 22.5-degree step changes the head angle and eye line by a small comparable amount, about one source pixel of facial cue movement. Major axes must remain readable while near-cardinal neighbors may be subtly different. Preserve the same body, pixel scale, skull volume and grounded registration across the loop. Row 10 starts one step after row 9 and closes smoothly at up. Cardinal clarity takes priority over literal fine angle accuracy, but never change the native pixel eye design.

Standard atlas body is about155px high with feet at201 in a192x208 cell; reference contact sheet and neutral idle frame govern final registration. Generator should use the same body size throughout its source strip. Deterministic assembly handles the final scale. No labels, markers, shadows, textures or detached effects.



## look-row-9

Make a single horizontal sprite animation strip of the TERRARIA GUIDE NPC, matching the attached official sprite and canonical base exactly. Flat pure #FF00FF background. EXACTLY EIGHT full-body figures with generous spacing. Same coarse square pixels, brown hair, grey sage shirt, blue trousers, tiny original white/dark eye. No props, scenery, decorations, text or labels.

The last input is four approved cardinal examples ordered UP, RIGHT, DOWN, LEFT. Use those poses as anchors. Output EIGHT poses left-to-right: (1) look UP, (2) look UP and slightly RIGHT, (3) look diagonally UP-RIGHT, (4) look RIGHT and slightly UP, (5) look directly SCREEN-RIGHT, (6) look RIGHT and slightly DOWN, (7) look diagonally DOWN-RIGHT, (8) look DOWN and slightly RIGHT. This is one coherent clockwise head-attention arc. Nose and eye face the image RIGHT side for all nonvertical poses, becoming lower toward the end.

Keep feet, legs, lower torso planted, same stance, same scale and baseline in all eight poses. Only head/neck yaw and pitch, original eye pixels and subtle shoulders change. Preserve skull, hair and tiny face pixel proportions. No enlarged eyes. No whole-body rotation. Each pose fully separated on magenta, no overlap or clipping. Use contact sheet for identity and consistent sprite size; use layout guide for spacing only, never draw its marks.


## look-row-10

Create one 8-pose sprite strip of the Terraria Guide, strict original coarse pixel style, pure #FF00FF background. First input shows the required SCREEN-LEFT facing. Use its face profile: visible nose protrudes beyond the LEFT cheek, tiny white/dark eye on the LEFT side of face, back of hair on the RIGHT. Preserve this unambiguous left profile for poses 3,4,5,6,7. These are head turns, with the feet/torso staying as stable as the completed look row reference.

EXACTLY EIGHT separated full-body figures left-to-right:
1. head bowed straight DOWN, centered
2. DOWN and slightly LEFT
3. diagonally DOWN-LEFT, nose projected left and low
4. SCREEN-LEFT with a small downward pitch
5. complete unmistakable SCREEN-LEFT head profile, level eye, nose projecting left
6. SCREEN-LEFT with a small upward pitch
7. diagonally UP-LEFT, left-facing nose raised
8. UP and slightly LEFT, head nearly centered and raised to match the first UP pose of the completed previous row.

No front-looking or right-looking face in poses 3-7. Do not merely tilt a front face. Keep one visible tiny original eye in side profiles; no large googly eyes. Match the supplied Guide's orange-brown block hair, grey sage shirt, dark blue trousers, sourcepixel head/body proportion, and square hard pixel edges. Same figure size, feet position and lower body throughout. The final input is completed first-half row: keep identical scale and body registration; start one step after its last bowed-right pose and end one step before its UP pose.

Use all other images as identity/layout references only. Four-anchor strip means UP/RIGHT/DOWN/LEFT. One horizontal row, fullbody, generous magenta gaps, no labels or drawn grid. No props, decorations, scene, glow, shadow, detached objects, blur or smooth rendering. Do not redraw a complete atlas. Only these8 left-half looking poses.
