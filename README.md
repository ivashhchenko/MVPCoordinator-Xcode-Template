## Ready-to-use template with custom MVP architecture + Coordinator

* Add this file to Library -> Developer -> Xcode -> Templates (If it exists, if not, you need to create it) -> Project Templates (Same)

### Since Xcode Templates doesn't let you configure everything with temaplateInfo.plist, here are the changes you need to make for the project to work:
* Add Application Scene Manifest parameter in Info.plist (Location: General - App Target - Info - Custom iOS Target Properties)
  <img width="840" alt="Screenshot 2024-05-15 at 16 07 02" src="https://github.com/ivashhchenko/MVPCoordinator-Xcode-Template/assets/95596580/269f20c6-3483-48c8-a3c3-02aadcc11467">

### That's it!

----------------------------------------------------------------------------------------------------------------------------------------------------

# Editing file locations

## If you don't like the hierarchy I'm using, you can edit it. To do this:
* Firstly, you need to change the location of the files in the folders in the archive

* Secondly the location is directly described in TemplateInfo.plist, in order to change it you need:
  
    Change the necessary file in "Definitions":  
    * _‘Group’ array contains the folders that should be created by Xcode in the correct sequence_
    
    * _'Path' value contains the full location of the file_
    
    <img width="717" alt="Screenshot 2024-05-15 at 16 32 34" src="https://github.com/ivashhchenko/MVPCoordinator-Xcode-Template/assets/95596580/9409acc7-46a9-411e-92b1-a5b3eab43317">

* Thirdly, you must also change the location of files in Nodes:  
  The principle is the same, you need to specify the full path to the file
  <img width="943" alt="Screenshot 2024-05-15 at 16 44 48" src="https://github.com/ivashhchenko/MVPCoordinator-Xcode-Template/assets/95596580/95614736-e018-4a58-b4ea-f01cc4b5fae6">
