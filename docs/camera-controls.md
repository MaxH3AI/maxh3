# Plan a camera move from one image

Use the [H3 Max Camera Controls workspace](https://www.maxh3.com/h3-max-camera-controls) when your main decision is a camera path around a starting image.

## Start with a readable image

Choose a subject with space around it and clear separation from the background. A camera move may reveal areas that are not visible in the source image; treat those newly generated details as an interpretation, not a reconstruction of a measured 3D scene.

## Design the ending first

Decide whether the shot should end closer, farther away, higher, lower, or at a different angle. Build a simple path between the initial view and that ending using the controls exposed in the workspace.

For the first experiment, keep the subject still and change only the camera. Avoid requesting several large direction changes in a short clip. Review the current workspace for available timing, path controls, and output options.

## Diagnose the result

| Observation | Next experiment |
| --- | --- |
| The subject leaves the frame | Reduce the move or start with more space around the subject |
| New surfaces look inconsistent | Use a smaller angle change and a clearer source image |
| Movement feels rushed | Reduce travel distance or choose a longer supported duration |
| Prompt and path appear to conflict | Remove competing camera directions from the text |

These are experiment suggestions, not verified fixes for every model output. Keep your source and other settings constant when comparing two paths.
