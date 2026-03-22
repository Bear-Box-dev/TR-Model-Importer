Tales Runner Model & Material Importer
A Blender Python script designed to streamline the process of importing 3D models from the game Tales Runner. This tool automates the tedious process of setting up materials and linking textures by reading the game's native .pt1 configuration files.

✨ Features
Automated Material Setup (TR_IMPORT_PT1): Automatically generates materials, builds shader nodes, and links the correct diffuse/alpha textures (.png or .dds) to your model based on the .pt1 file data.

Blender 5.1+ Compatibility: Uses modern Eevee Next shader configurations for accurate alpha and transparency rendering without manual node tweaking.

⚠️ Prerequisites
Before using this script, you must extract the game's assets from the .pkg archives to get the raw model and texture files.

Download the Tales Runner PKG Tool by sup817ch.

Extract your target .pkg file using the tool.

Ensure that your extracted model file (e.g., .m1), the .pt1 file, and the texture files are located in the same directory.

🚀 Installation
Download the script file (TR_IMPORT_PT1.py) from this repository.

Open Blender.

Go to the Scripting workspace tab at the top.

Click Open and select the downloaded script file, or simply paste the code into a new text block.

📖 How to Use
To successfully apply textures to your model, follow these exact steps:

Import the Model: First, import your base model into Blender.

Select the Object: In the 3D Viewport or Outliner, click to select the imported model (it should have an orange outline indicating it is the active object). Note: The script will not run if a mesh is not selected.

Run the Script: In the Scripting workspace, click the Run Script button (the play icon ▶ or Alt + P).

Choose the PT1 File: A file browser will pop up. Navigate to the folder containing your extracted assets and select the .pt1 file that corresponds to your model.

Done! The script will automatically parse the file, create the necessary materials, and apply the textures to your model. Switch your Viewport Shading to "Material Preview" to see the result.

🤝 Credits & Acknowledgments
Massive thanks to sup817ch for creating the PKG extraction tool that makes accessing these files possible.
