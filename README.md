MediaPipe component
Option for auto-assigned network port now the default - port is assigned by OS to avoid conflicts (enabled by default)
Websocket path parameter removed to tidy up UI
Webcam start error now works more reliably #42
Webcam error asks if you have the webcam running somewhere else (most common cause of webcam failing to start in MP)
Hopefully less eternal loading screens!
Error message clears if webcam successfully starts
Error message if local files are missing and you downloaded the dev version
Bumped JS dependencies:

mediapipe 0.10.8
vite 4.5.0
typescript 5.2
yarn 1.22.20
face_tracking
Supports up to 5 faces at once 🎉
Blend shapes and transformation matrix now output properly for facial landmarks #54
Pose
Supports multi-pose (needs example parsing multiple poses)
object_tracking
Object tracking bounding boxes fixed #36
Max number of objects to detect now works correctly
face_detector
Face tracking bounding boxes and confidence labels added
General
Added annotation for Video Device In / Syphon Spout Out TOP chain
