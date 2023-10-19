# Red-Picker-App-Java-Interface
The JavaFX application counts the amount of red color at the point of clicking and arranges the slices in descending order of the average red component.

## Tech Stack
* JAVA 17
* JavaFX
* CSS
* SceneBuilder


## Logic

 ![InterfaceHomeWork2](https://github.com/KateStar-git/Red-Picker-App-Java-Interface/assets/123861976/4b1f55f9-305e-4c0e-96e7-af8f6ac94e66)
 
The box on the right side of the window contains an image. After starting the application, the field may be empty or contain a default image.

After clicking the ,,Load" button, a file selection dialog opens. After making your selection( select jpg file: apples2.jpg), the image is shown in the field on the left.

Each click on the image causes:
* calculation of the average value of the red component of pixels in a 41x41 square (the place of clicking is the center of the square)
  
* copying the contents of the square to one of the 25 fields on the right side of the window - the slices are arranged in descending order of the average value of the red component of the pixels in the square. If all fields are occupied and the new slice has a red component value greater than the component in the last square, the slice from the last field is deleted and the newly copied one is inserted in the right place.
 

After clicking the ,,Clear" button, all fields containing image clippings are cleared.






  

