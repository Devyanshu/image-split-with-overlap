## Split any image with any degree of overlap.
### Divide image of any size into smaller images of fixed size with any degree of overlapping.

#### Overlapping means some part of the previous image is repeated in the current image. For example, 50% overlap means half of the previous image is repeated in the current image, both horizontally and vertically.

#### If the image is not completely divisible, the degree of overlapping on the boundary images are increased such that they become divisible.

### Example 
#### Sample Image(580x435)
![Sample Image](images/sample.jpg)

#### Splitted images(150x150) with 50% overlap


| ![Splitted Image](images/splitted_0.jpeg)  |  ![Splitted Image](images/splitted_1.jpeg) |  ![Splitted Image](images/splitted_2.jpeg) | ![Splitted Image](images/splitted_3.jpeg)  | ![Splitted Image](images/splitted_4.jpeg)  |  ![Splitted Image](images/splitted_5.jpeg) |  ![Splitted Image](images/splitted_6.jpeg) |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| ![Splitted Image](images/splitted_7.jpeg)  |  ![Splitted Image](images/splitted_8.jpeg) |  ![Splitted Image](images/splitted_9.jpeg) | ![Splitted Image](images/splitted_10.jpeg)  | ![Splitted Image](images/splitted_11.jpeg)  |  ![Splitted Image](images/splitted_12.jpeg) |  ![Splitted Image](images/splitted_13.jpeg) |
| ![Splitted Image](images/splitted_14.jpeg)  |  ![Splitted Image](images/splitted_15.jpeg) |  ![Splitted Image](images/splitted_16.jpeg) | ![Splitted Image](images/splitted_17.jpeg)  | ![Splitted Image](images/splitted_18.jpeg)  |  ![Splitted Image](images/splitted_19.jpeg) |  ![Splitted Image](images/splitted_20.jpeg) |
| ![Splitted Image](images/splitted_21.jpeg)  |  ![Splitted Image](images/splitted_22.jpeg) |  ![Splitted Image](images/splitted_23.jpeg) | ![Splitted Image](images/splitted_24.jpeg)  | ![Splitted Image](images/splitted_25.jpeg)  |  ![Splitted Image](images/splitted_26.jpeg) |  ![Splitted Image](images/splitted_27.jpeg) |
| ![Splitted Image](images/splitted_28.jpeg)  |  ![Splitted Image](images/splitted_29.jpeg) |  ![Splitted Image](images/splitted_30.jpeg) | ![Splitted Image](images/splitted_31.jpeg)  | ![Splitted Image](images/splitted_32.jpeg)  |  ![Splitted Image](images/splitted_33.jpeg) |  ![Splitted Image](images/splitted_34.jpeg) |


### Image splitting can be used to
 - Get fixed size images from image of any size.
 - Generate partial fingerprints from any given fingerprint sample.
