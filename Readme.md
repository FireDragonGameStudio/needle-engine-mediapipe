# Needle Engine and Media Pipe tasks-vision
A small prototype to show Needle Engine (https://engine.needle.tools/docs/getting-started) in combination with MediaPipe (https://www.npmjs.com/package/@mediapipe/tasks-vision), based on their sample, which can be found either within their samples dev branch (https://github.com/needle-tools/needle-engine-samples/blob/dev/package/Runtime/Mediapipe/needle-mediapipe~/MediapipeHands.ts) or in the Needle Engine docs (https://engine.needle.tools/docs/scripting-examples.html#use-mediapipe-package-to-control-the-3d-scene-with-hands).

## Quickstart
Recreating this project is fairly easy, as all scripts are already existing. The only thing to do (after creating a new Needle Engine Blank project) is to open your dev environment (via clicking on "Open workspace" on your Export gameobject) and open the Terminal for your project. Run "npm i @mediapipe/tasks-vision" to install media pipe npm package and you're ready to go. Finally copy the scripts from the docs or usethe ones from within this project and run the project in your browser. a working version can be found here - https://fdgs-needle-mediapipe.glitch.me/

## Informal
This is just a sample implementation and will very likely NOT be maintained actively. Tested on FF and Chrome. When working with hand tracking, make sure to have sufficient lighting, because of the camera based hand recognition!
