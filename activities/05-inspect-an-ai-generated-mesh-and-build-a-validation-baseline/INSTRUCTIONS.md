# Instructions — Activity 5

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Copy the starter asset to a BASELINE folder and mark it read-only or preserve it unchanged.
2. Open a working duplicate and record Blender version, object count and collection names.
3. Check scene units, object dimensions, location, rotation, scale and origin.
4. Enable viewport statistics and record vertices, edges, faces and triangles.
5. Inspect the model in front, side, top and perspective views.
6. Use Face Orientation to check outward-facing surfaces.
7. In Edit Mode, use Select > Select All by Trait > Non-Manifold and count affected elements.
8. Check for disconnected shells, internal faces and duplicate vertices.
9. Review modifier stacks and note any warnings or unapplied dependencies.
10. Capture consistent screenshots of every blocking defect.
11. Classify findings as blocker, major, minor or observation.
12. Populate the validation dashboard without repairing the mesh yet.
13. Save the working inspection file separately from the baseline.

## Expected result

A frozen baseline Blender file, defect register and validation dashboard.

## Evidence to include

- Baseline metadata
- Statistics screenshot
- Face Orientation view
- Non-manifold selection
- Defect register

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
