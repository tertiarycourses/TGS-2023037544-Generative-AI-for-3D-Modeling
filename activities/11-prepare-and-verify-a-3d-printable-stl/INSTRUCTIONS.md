# Instructions — Activity 11

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Confirm intended print size, material/process, minimum wall thickness and required clearances.
2. Duplicate the approved source and remove decorative geometry not intended for printing.
3. Set scene units and verify the target dimensions in millimetres.
4. Join or boolean parts only where the physical prototype must be one connected volume.
5. Add or verify wall thickness and inspect narrow features against the process limit.
6. Use Non-Manifold selection and Face Orientation to verify a closed outward-facing surface.
7. Check for disconnected shells, internal faces and self-intersections.
8. Choose an orientation that reduces support and protects critical surfaces.
9. Apply required modifiers in the export copy while preserving the editable master.
10. Export STL using the documented unit setting.
11. Re-import the STL into an empty Blender file and verify dimensions and surface orientation.
12. Open the STL in a slicer when available and record warnings, support estimate and print time.
13. Package the STL, source file, screenshot and limitations note.

## Expected result

A millimetre-scale STL, printable-source Blender file and slicer-readiness checklist.

## Evidence to include

- Dimension screenshot
- Manifold/Face Orientation checks
- Wall-thickness evidence
- Re-import comparison
- Slicer or readiness report

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
