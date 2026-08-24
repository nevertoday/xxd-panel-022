# XXD Panel 022 | Clean-Line Black-Field Breakout + One Colour Signal

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the one source photograph explicitly supplied for the current task. Lock one principal subject or inseparable relation, its main action, and at least three source-specific cues. Never borrow a subject, field orientation, breakout device, line character, copy, or composition from samples, old outputs, or another input.

## Black visual field and genuine breakout

Choose one horizontal or vertical pure-black rectangle from source weight, contour flow, and action direction. Most of the subject must exist inside it. Select exactly one most distinctive head, top contour, branch, roof, limb, object edge, or other key structure as the breakout focus.

The subject must feel as if it emerges from, passes through, grows out of, or breaks the black space. The rectangle is simultaneously background, space, and compositional structure. Never draw a complete subject over a decorative rectangle, let several parts break out equally, or reduce the field to a pasted colour block.

## Clean stable hand line and negative shape

Retain only essential outer contour, pose, and key structure. Draw with concise, smooth, stable black hand line carrying natural elasticity and rhythm. Allow slight human variation, but reject conspicuous jitter, repeated tracing, hairy noise, random breaks, deliberate awkwardness, and sterile machine-uniform vector line.

Use white negative form and very small grey planes for recognition, with only a few expression, construction, fold, or local shadow lines. Never fill the subject as a pure black silhouette. Reject broad greyscale, realistic shading, gradients, airbrush, 3D volume, and complex internal rendering.

## Exactly one colour signal

Extract one representative highlight colour from the source and modestly purify it. Apply it to exactly one smallest decisive detail: a body part, small object, key surface, action focus, or emotion signal. The accent must be tiny, precise, narratively useful, and feel like the only illuminated point in the image. Reject a second accent colour, broad colour area, global tinting, gradients, decorative swatches, or arbitrary colouring.

## Geometric order versus free contour

The black rectangle carries geometric order; asymmetric placement, local crop, and breakout create life. Surround the field with generous pure-white paper for a strong restrained black/white/grey area relation.

Allow only a few straight lines, inclined planes, platforms, edges, or geometric slices when they support scale, direction, boundary, or breakout action. Reject complex scenes, a second subject, decorative frames, template centring, and unrelated symbols.

## Typography belonging to 022

Obey the locked automatic, exact-user, or text-free copy mode and target language or locale. Preserve exact user wording verbatim. In text-free mode render no letter, character, number, or pseudo-text.

Automatic copy derives one short title from action, emotion, state, relation, or a grounded metaphor, then adds one to three tiny annotations, indexes, state words, or phrases. Factual numbers, places, dates, and provenance require user input or reliable evidence.

Attach type to the black-field edge, hide it in white negative form, follow the breakout direction, or align and deliberately misalign it with subject contour. Use small black handwriting, slender sans, or restrained serif so it reads as an illustrator's annotation and editorial mark rather than a commercial title or signature.

Preserve native shaping, joining, spacing, direction, punctuation, and semantic line breaks. Never force Latin tracking, rotation, or handwriting logic onto Chinese, Japanese, Korean, or Arabic.

## Mode and hard gate


Hard gate: one pure-black horizontal or vertical rectangle; most of the subject inside it; exactly one defining structure genuinely crosses the boundary; at least three source cues and the principal action remain legible; concise, smooth, stable black illustrator line with natural elasticity; white negative form plus tiny grey planes; exactly one tiny, precise, source-derived, narratively useful colour accent; generous white paper, asymmetric placement, and local crop; one short title plus one to three micro-groups enter the field edge, negative shape, breakout direction, or contour; no jittery broken retracing, hairy noise, pure silhouette, multiple or broad colours, sterile vector, complex scene, realistic shading, 3D, template centring, or pseudo-text.

If any hard condition fails, correct the generated asset. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, or a post-composited type overlay.
