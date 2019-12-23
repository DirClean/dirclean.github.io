# What is "prevent"?

> Warning: This feature is designed for advanced users.

In Android devices, files and folders cannot have the same names in the same folder. For example, I have a folder named "Pictures", and it contains a file called "Camera", or vice versa.

Dir uses this technology to prevent deleted files being created again. How it does is to create a empty file (we call it a "placeholder") with the same name of the deleted folder. For example, Dir deleted a folder called "Ads", and it will create a new empty file and name it "Ads", so other programs will not be able to create the same folder again. 

However, any programs can modify your storage. If a program deletes the placeholder, it will no longer work. Therefore, we provide an option to create the placeholder using Root. It will protect the placeholder from deleting.

As far as we know, this method only works with folders. However, if you enabled the root option, it will create an empty file after deleting a file as well, then using Root to protect us from being written.

This function looks great, but it usually leads to problems. Sometimes programs will encounter errors since they cannot create folders. If you enabled the Root option, they may not being able to write the placeholders. If the placeholders are for advertisement files or other files that you do not want programs to create, there's no problem. The problem is that some folders may contain necessary data for apps to work, and preventing them will lead to errors. If so, you have to undo prevents.

Undo means to delete the placeholder (using root if you previously chose), so other programs will be able to create folders. It is exteremely helpful if you found that some apps or functions stop working after preventing some folders.
