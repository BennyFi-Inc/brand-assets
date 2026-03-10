# BennyFi Brand Assets

Branding materials, logos, and video assets for all BennyFi projects.

## Structure

```
bennyfi/              Core BennyFi brand
  logos/              Logo variations (SVG, PNG)
  colors/             Color palettes, swatches
  fonts/              Brand typefaces

pledgepool/           PledgePool branding
  logos/
  colors/

flipstake/            FlipStake branding
  logos/
  colors/

pokerpledge/          PledgePoker branding (name TBD — see agents #5)
  logos/
  colors/

video/                Video production assets
  explainer/          BennyFi explainer video (agents #2)
  flipstake/          FlipStake explainer (agents #4)
  pokerpledge/        PledgePoker explainer (agents #5)
```

## Usage

These assets are used by the videographer agent (`bennyfi-agents`) and marketing materials. Reference images can be passed to Veo 3.1 for consistent branding in generated videos.

## Guidelines

- Logos: provide SVG (vector) + PNG (raster, transparent background)
- Minimum sizes: 512x512 for social, 1920x1080 for video
- Color palettes: include hex codes in a `palette.md` file per project
- Do not commit PSD/Figma source files — link to Figma instead
