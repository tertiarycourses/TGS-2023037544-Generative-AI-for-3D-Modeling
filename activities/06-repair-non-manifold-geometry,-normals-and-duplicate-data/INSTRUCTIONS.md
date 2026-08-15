# Instructions — Activity 6

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Duplicate the working object and suffix the copy _REPAIR while preserving the baseline.
2. Apply scale only after confirming the dimensions and recording the reason.
3. Enter Edit Mode and run Merge by Distance with a conservative threshold.
4. Review the status message and record how many vertices were merged.
5. Use Non-Manifold selection to isolate the open boundary.
6. Rebuild the smallest necessary faces or bridge compatible edge loops.
7. Inspect for internal faces around the repaired area and delete only confirmed internal geometry.
8. Select all faces and recalculate normals outside.
9. Enable Face Orientation and confirm no unexpected inward-facing patches remain.
10. Apply smooth shading and configure sharp edges or normals deliberately.
11. Repeat the non-manifold, dimensions and silhouette checks from Activity 5.
12. Compare polygon statistics and note any material or UV impact.
13. Save a new version and update the defect register to closed or open.

## Expected result

A repaired manifold model with before/after evidence and regression results.

## Evidence to include

- Before/after Face Orientation
- Merged-vertex count
- Repaired boundary close-up
- Regression table
- Versioned Blender file

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
