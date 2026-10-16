# Generation prompt (image, from `front-view.png`)

Reference: render run `27f47351a66a4ff5a89c6802b6ea4db8`, frame 0, camera `cam-main` (front view).
Service used: Canva generate-image with the render as an image reference.

```text
A photorealistic, warm daylight photo of a cheerful 7-year-old Asian child with short black hair and
dark black eyes, smiling happily, sitting on a wooden garden bench. The child leans slightly forward
with hands clasped in their lap and is turned a little toward their right, toward a colourful school
backpack with a front pocket that stands on the grass by their right foot (lower left of the frame).
Their feet dangle above the ground because the bench is a little too tall for them. Behind the bench
are rounded green bushes and two leafy trees in a sunny garden with a lawn; soft natural light,
shallow depth of field, eye-level front view.
Keep the exact layout, framing, camera angle and positions of the reference image: the child
centred-right on the bench, the school bag on the ground at lower left, bushes and trees behind.
Do not copy the grey mannequin look, the plain grey shapes, the grid floor or the flat shading of the
reference; render real materials, skin, hair, clothing, grass and leaves.
```

## Result (2026-10-16)

- Canva: the reference upload was blocked by the cloud network policy, and text-only generation
  failed with `quota_exceeded`.
- Gamma `generate_image` (type photo, 16:9, text prompt only, **no reference image attached**):
  completed, 2752×1536, 70 credits.
  Image: https://cdn.gamma.app/gge0b7sgvfnimcc/design-anything/0Sweyy3cBmeeUksh2bdZc/XwGfFtEHxJhOprh0xvGyQ.jpg
  (link may expire; also saved in the Gamma media library). Not yet visually checked against the
  staging render.
