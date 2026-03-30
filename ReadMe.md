# EvaluatePictures
This program allowes to quickliy group Pictures by moving them into subfolders with keyboard shortcuts

## Requirements
- Linux
- Java
- Imageviewer
```bash
sudo apt install hfsdjfhkdf
```

## How to use
1. Download ./build/evaluatePictures.jar
2. Run
```bash
java evaluatePictures.jar /FolderPath [-d|r]
```

This iterates trought the given Folder (not recursive) displaying each image.<br>
By default images are sorted by name, ascendingly.<br>
Optionally use -d to sort by date and -r to reverse order.<br> 

When the image is displayed press >0< to move the image to folder /FolderPath/1/imageName and go to the next image<br>
possible inputs 0,1,2,...,9<br>



