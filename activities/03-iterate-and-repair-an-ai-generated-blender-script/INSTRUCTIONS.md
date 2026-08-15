# Instructions — Activity 3

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Open the starter file and save a diagnostic working copy.
2. Open the supplied faulty script and read its intended outcome before running it.
3. Run the script once and copy the complete traceback, including the failing line.
4. Classify the failure as syntax, missing data, context/mode or API-version mismatch.
5. Inspect the Outliner for any partial objects created before the failure.
6. Ask the AI assistant to repair only the failing section, providing the Blender version, full traceback and intended outcome.
7. Review the proposed patch for new destructive operations or unrelated rewrites.
8. Apply the smallest change and rerun in a clean duplicate of the starter file.
9. Run the repaired script a second time to test idempotence and check for duplicates.
10. Compare object names, modifier stacks and geometry against the expected example.
11. Record the root cause, repair and regression checks in the presentation.
12. Save the final script and Blender file with a new version number.

## Expected result

A repaired rerunnable script, an error log and a before/after diagnosis.

## Evidence to include

- Error screenshot
- Root-cause statement
- Before/after code excerpt
- Two-run Outliner check
- Final script and .blend

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
