# Instructions — Activity 2

## Before you begin

- Use Blender and work only on a copy of the starter file.
- Preserve the original input and save incremental versions.
- Capture evidence at the points named below.

## Step-by-step

1. Open the starter Blender file and save a working copy inside the activity folder.
2. Confirm the installed Blender version from Help > About Blender and record it.
3. Ask the AI assistant to write a Blender Python script for that version which creates a UV sphere named AI_GoldSphere, gives it a gold Principled BSDF material, adds a floor, light and camera, and does not save or overwrite files.
4. Review the script for broad delete commands, file-writing commands and unnamed objects before running it.
5. Switch to the Scripting workspace and create a new text block.
6. Paste the reviewed script into the text editor.
7. Run the script and watch the status bar and system console for errors.
8. Return to the Layout workspace and switch to Material Preview or Rendered view.
9. Verify that AI_GoldSphere exists, uses the gold material and is positioned above the floor.
10. Check the Outliner for clear names and confirm the sphere scale is 1, 1, 1.
11. Render one camera view and save the image in the evidence folder.
12. Save the Blender file as Activity-02-Gold-Sphere-Completed.blend.
13. Update the sample presentation with the prompt, script review, result and verification evidence.

## Expected result

A safe Blender script, a generated gold sphere scene and an execution evidence presentation.

## Evidence to include

- Exact prompt
- Reviewed script
- Outliner screenshot
- Rendered result
- Completed .blend file

## Troubleshooting

- If an AI-generated script fails, copy the complete traceback and the Blender version; ask for the smallest relevant repair.
- If a modifier or bevel looks inconsistent, verify object scale before changing geometry.
- If an export looks wrong, re-import it into a clean file and compare dimensions, normals, hierarchy and materials.
- Never overwrite the preserved starter or baseline while diagnosing.
