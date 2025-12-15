# polytrack_TAS
Tool Assisted Speedrun

## Requirements
Software: Anything that can serve static html/js/css files from the /public folder. This can be the nodejs express server I provided (`npm i`, `node main.js`) or a python server (`cd public`, `python -m http.server`).  
Hardware: About 1.3 GB of RAM. My modified ammo.wasm.wasm file allocates 16x more RAM than normal Polytrack in order to simulate many more tracks/cars at once. Preallocation of about 1.15GB.

## Usage
Go to `localhost:19998/replay_editor` to view an example of a 2D path of the car based on a track code (hardcoded in 'ai_environment.js') and inputs (in customInputs.js).

More documentation will follow soon.