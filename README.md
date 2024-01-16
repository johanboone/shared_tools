# shared_tools
To share tools developed by Johan Boone, Witteveen+Bos, with external partners.

#Installation instructions
- Navigate to this folder: %\AppData\Roaming\Autodesk\Revit\Addins\2024\
- Place the following files in this folder:
    VTTITools.addin
    VTTITools.dll
    VTTITools.dll.config
- Open the VTTITools.dll.config with a text editor and make sure that the 'DataDirectory' variable points to the location of the VTTIdata folder on your pc.
    The VTTIdata folder contains the lines from C3D as text. This data is used by the addin to place the elements correctly in the model.
    The VTTIdata folder should be placed in the same folder as the other files.
- If you received the addin via email or as a .zip file, make sure to Unblock all the files before starting Revit.
  See: https://www.404techsupport.com/2016/06/24/unblock-files-powershell/
