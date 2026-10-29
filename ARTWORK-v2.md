# Artwork and assets

## Banner subtitle removal

The current banner was edited with the built-in imagegen tool to remove its subtitle while preserving the illustration.

```text
Use case: precise-object-edit.
Edit target: the supplied existing GitHub banner.
Make exactly one localized change: erase the small white subtitle "code, circuits & anime" below the large lavender handwritten name "Verskud" on the LEFT wall. Restore the dark painted wall texture naturally behind ONLY those small subtitle letters. Leave that subtitle area blank; do not replace it with any new words.
Preserve the large "Verskud" name exactly, all lime-green underline strokes and stars, the character Arcane's face, eyes, silver hair, head ornaments, clothing, pose, hands, held PCB, every other element of the room, circuit boards, desk objects, monitors, waveform display, stickers including "unsafe {}", the composition, lighting, color grading, and overall 3:1 panoramic dimensions. Do not redraw or restyle the illustration. No other changes. The user likes the illustration and only wants this subtitle removed.
```

## Original artwork

The banner and matching avatar are original AI-generated fan artwork made with the built-in imagegen tool. The character identity reference is [Arcane's official Arknights: Endfield portrait](https://endfield.gryphline.com/en-us/operator). Arcane belongs to HYPERGRYPH / GRYPHLINE. This is an unofficial fan profile, with no affiliation with the game.

- `assets/banner-clean.png`: profile cover, with the subtitle removed.
- `assets/avatar-arcane.jpg`: matching avatar, encoded as JPEG below GitHub's 1 MB upload limit.
- `assets/avatar-arcane-500.png`: avatar upload version, 500 by 500 pixels, below 1 MB.
- `assets/badge-c.svg`, `assets/badge-cpp.svg`, `assets/badge-rust.svg`: local vector language badges, using [Simple Icons](https://github.com/simple-icons/simple-icons) under CC0.

The previous visual design is preserved in Git history at commit `a66bde2996471e558e967a8ff3b68dfa0782dfb2`.

## Avatar prompt

```text
Use case: stylized-concept
Asset type: square GitHub profile avatar, final original anime fan art, 1024x1024.
Primary request: Arcane from Arknights: Endfield as the avatar of a knowledgeable anime nerd who loves embedded programming and electronics. This should feel like a coveted anime forum/reddit profile picture with real personality, not corporate AI promotional art.
Reference image is the exact character identity: preserve silver-white hair with pale cyan undersides, black feather-like headset ornaments, vivid violet and pink eyes, narrow red forehead mark, black technical collar and small red details. Adult anime woman.
Composition: extremely striking head-and-shoulders close portrait, three-quarter angle, both eyes readable, looking at viewer with a quiet slightly smug half-smile. Head, ornaments and shoulders entirely inside a circular crop safe zone; the face fills the center. Hair has beautiful sharp expressive illustrated shapes, not hundreds of noisy random strands.
Style: hand-drawn late-2000s premium anime key visual meets a contemporary indie manga artist; crisp black linework, slightly grainy cel shadows, strong graphic light and expressive eyes. No 3D/plastic skin. A dark hoodie layered over her technical collar. Tiny lime PCB-shaped pin, a restrained piece of microelectronics personality.
Background: dark charcoal with one desaturated lavender circular field and a few electric-lime crosshatch marks. Editorial manga texture, very restrained. White hair against dark background, vivid violet eyes. Great contrast and instantly recognizable even at 64px.
No text, no initials, no border, no logo, no watermark, no extra characters, no extra arms, no sexualization. The mood is anime geek who knows what she is doing, deadpan and cool.
```

## Banner prompt

```text
Use case: illustration-story
Asset type: extra-wide 3:1 GitHub banner, approximately 2400x800, original anime fan-art illustration.
Primary request: A personal anime nerd's late-night electronics corner featuring Arcane from Arknights: Endfield. Rich, charming, tastefully chaotic anime forum / reddit tinkerer aesthetic. An actual illustrated scene with personality, not a corporate portfolio, not a UI dashboard, not a giant name beside a glamorous generic portrait.
Reference image defines the character identity: Arcane's silver-white and pale cyan hair, dark feather-like headset ornaments, violet eyes, red narrow forehead mark, familiar dark technical collar. Adult anime woman. She wears a loose black hoodie over that collar, casual and fully clothed.
Scene: Arcane occupies center-right, leaning on one elbow at a small crowded electronics workbench, holding a small circuit board carefully with one gloved hand, looking toward the viewer with a quietly knowing half-smile. Hand-drawn anime art, clean expressive outlines, beautifully composed cel-shaded forms with subtle ink and screentone texture. PCB, fine probes, a soldering station, breadboard, loose electronic components, and a logic analyzer screen with meaningful clean square-wave traces are drawn as charming environmental details. Several scattered manga screentone fragments, a tiny pixel star and an "unsafe {}" sticker on a device. Black-and-lavender with a few acid lime accents and soft silver hair.
Composition: comfortably readable wide scene, whole face stays inside frame. Left third has the text integrated as a casual manga title over a charcoal wall, not a corporate headline. A slight diagonal zine layout and cropped background shelves. Main text small-to-medium and lowercase, verbatim: "verskud". One small secondary text line below it, verbatim: "code, circuits & anime". These are the only readable words apart from the small "unsafe {}" sticker. No giant skill list on this illustration.
Lighting: warm neutral workbench light plus lavender monitor light, intimate lived-in technical den. Muted graphite #15151c, dusty lavender #bba3df, acid lime #c1e88d accents, icy white hair. Detail is concentrated around the character and bench, generous quiet space at left.
Avoid: photorealism, 3D render, airbrushed plastic face, polished sci-fi recruitment poster, generic neon cyberpunk, gratuitous HUD, badges, large logos, fake statistics, watermark, extra characters, sexualized pose.
```
