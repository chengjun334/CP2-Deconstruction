# CP2-Deconstruction


## Mikutap
link: https://aidn.jp/mikutap/



Guided message: Click/Drag/Press any key

Dividing the screen into 8x4=24 areas, and each area corresponds to a sound and animation. So are the keys.
Click or drag or press keys will trigger the corresponding sound or animation.
Color is changing randomly


## Deconstruction System Diagram

| Data | Render | Simulation | Events |
| ------------- | ------------- | ------------- | ------------- |
| input:Keypressed | animation activates | color changing in the background | Feedback on will display the clicked area.  |
| input:Mouse's movement | Radom color | Shapes disappear after zoom-in animation ends | Backtrack on will It will loop music. |
| library:sounds | sounds activate | / | / |
| Geometric shapes | Image rotation | / | / |
