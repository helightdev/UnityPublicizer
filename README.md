# UnityPublicizer
This is a pretty lightweight publicizer utilizing **dnlib** for .Net assemblies, specifically made for **modding of non il2cpp built unity games**.
I do not guarantee that the dll will be usable after publicization since the publicized dll is just meant to be used for **Framework/Modloader development**
as resource for the editor & compiler since the access modifier can be ignored at runtime. 

## Usage
1. (optionally) Place the .dll you wan't to patch in the same folder as the publicizer executable
2. Drag and drop the .dll onto the executable
3. You can find the output files in the `/Delivery` folder. It will contain the original .dll as well as the publicized assembly

## Installation
You can download the latest working version via the gituhub releases.
