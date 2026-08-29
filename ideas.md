# Vertex Acupressure — Design Direction

## Three stylistic approaches

### Theme Name: Quiet Editorial
Very Brief Intro: A composed wellness editorial inspired by premium print magazines: warm mineral neutrals, black ink, sharp geometry, and a restrained amethyst accent. The product feels like a considered object, not a trend accessory.
Probability: 0.06

### Theme Name: Soft Recovery Studio
Very Brief Intro: A light, airy treatment-room aesthetic with chalky whites, soft sage, tactile paper textures, and gentle instructional photography. The emotional intent is restorative, accessible, and human.
Probability: 0.03

### Theme Name: Night Reset
Very Brief Intro: A dark, cocooning sleep-and-recovery experience using near-black surfaces, cool violet highlights, and slow ambient motion. It frames the mat as a nightly ritual.
Probability: 0.08

## Selected approach: Quiet Editorial

### Design Movement
Contemporary editorial minimalism with references to luxury magazine art direction, Swiss grid discipline, and the quiet authority of premium wellness packaging.

### Core Principles
1. **Calm authority:** use confident typography, short sentences, and generous negative space.
2. **Tactile contrast:** pair warm paper-like surfaces with black product imagery and a precise amethyst accent.
3. **Asymmetrical composition:** offset image and copy blocks so the page feels art-directed rather than templated.
4. **Useful clarity:** every section should answer a practical question or move the reader toward a considered purchase.

### Color Philosophy
The palette uses bone and oat to make the page feel grounded and breathable, ink to create editorial contrast, and Vertex amethyst as a singular signal for pressure-point energy. Amethyst is used sparingly so it reads as an ownable brand cue, not decoration.

### Layout Paradigm
A vertical editorial sequence with a split hero, oversized section numerals, offset content rails, and comparison content that reads like a product specification sheet. Full-width color fields alternate with narrow text columns to control pace.

### Signature Elements
- Oversized pale lavender section numbers aligned to the left rail.
- Thin rules, small uppercase labels, and annotation-like details inspired by product packaging.
- Amethyst dot clusters and soft circular halos echoing the mat's pressure-point flowers.

### Interaction Philosophy
Interactions should feel precise and reassuring. Buttons have a firm press response, navigation scrolls to practical answers, FAQ items open with a short controlled reveal, and no interaction should feel gamified or urgent.

### Animation
Use short opacity/translate entrances with 30–60ms staggered delays, a subtle product-image hover lift, and 180ms–240ms ease-out transitions. Respect reduced-motion preferences. Avoid looping decorative animation except for a very slow background grain or halo shift.

### Typography System
Display: Cormorant Garamond, 600, for poetic but grounded headlines. Body and interface: DM Sans, 400–700, for readable product information. Use uppercase DM Sans with tracking for eyebrow labels. Keep headline line lengths narrow and allow occasional italic emphasis in Cormorant.

### Brand Essence
Vertex is a premium, approachable acupressure ritual for people who want a calmer body in 10–15 minutes a day, with the mat-and-pillow set making the practice more complete. Personality: **grounded, exacting, restorative**.

### Brand Voice
Headlines are direct, sensory, and quietly confident. CTAs are invitational rather than pushy. Microcopy should explain what happens next and avoid wellness clichés.

Example lines:
- “A calmer body, one quiet interval at a time.”
- “The full-pressure set: mat below, neck support above.”

### Wordmark & Logo
Use the supplied Vertex logo as the primary mark. Pair it with a compact geometric vertex symbol in favicon-sized contexts; do not typeset the wordmark in a default font.

### Signature Brand Color
**Vertex Amethyst — #8D55B8**, used for pressure-point motifs, active states, and the primary CTA accent.

## Implementation notes

- Real supplied product imagery is the source of truth for the hero, gallery, and product detail moments.
- Testimonial copy remains clearly marked as placeholder content until the owner supplies real customer quotes; do not present invented social proof as live reviews.
- “Shop Now” and “Buy Now” are isolated checkout placeholder components with no custom cart or payment logic.
- The build remains frontend-only and deployable through GitHub/Vercel with no Shopify dependency.
