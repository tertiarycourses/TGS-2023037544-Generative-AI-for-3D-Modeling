# Instructions — Activity 8

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Apply scale after verifying the model dimensions.
2. Identify hidden or logical boundaries for UV seams.
3. Mark seams around openings, underside transitions and detachable parts.
4. Unwrap the model and inspect islands using a checker texture.
5. Correct stretched regions and equalise texel density across comparable surfaces.
6. Pack islands with appropriate padding and preserve intentional overlaps only.
7. Review the AI-assisted texture reference for baked lighting, text, logos and visible seams.
8. Clean the base-colour image into an evenly lit, tileable material where required.
9. Create a Principled BSDF material and connect base colour, roughness and normal channels using the correct colour-space settings.
10. Tune plausible metallic and roughness values under neutral lighting.
11. Inspect UV seams, repeated patterns and normal-map strength at close range.
12. Record texture provenance, resolution and any manual edits.
13. Save the packed/linked asset and update the evidence presentation.

## Expected result

A UV-mapped Blender asset, validated material channels and texture evidence.

## Evidence to include

- UV layout screenshot
- Checker test
- Shader graph
- Neutral-light material render
- Texture register

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
