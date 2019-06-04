## Split any image with any degree of overlap.
### Divide image of any size into smaller images of fixed size with any degree of overlapping.

#### Overlapping means some part of the previous image is repeated in the current image. For example, 50% overlap means half of the previous image is repeated in the current image, both horizontally and vertically.

#### If the image is not completely divisible, the degree of overlapping on the boundary images are increased such that they become divisible.

### Example 
#### Sample Image(580x435)
![Sample Image](images/sample.jpg)
#### Splitted images(150x150) with 0% overlap


| ![Splitted Image](images/0/splitted_0.jpeg)  |  ![Splitted Image](images/0/splitted_1.jpeg) |  ![Splitted Image](images/0/splitted_2.jpeg) | ![Splitted Image](images/0/splitted_3.jpeg)  | 
|:-:|:-:|:-:|:-:|
|![Splitted Image](images/0/splitted_4.jpeg)  |  ![Splitted Image](images/0/splitted_5.jpeg) |  ![Splitted Image](images/0/splitted_6.jpeg) | ![Splitted Image](images/0/splitted_7.jpeg) |
|![Splitted Image](images/0/splitted_8.jpeg)  |  ![Splitted Image](images/0/splitted_9.jpeg) |  ![Splitted Image](images/0/splitted_10.jpeg) |![Splitted Image](images/0/splitted_11.jpeg) |

#### Splitted images(150x150) with 10% overlap


| ![Splitted Image](images/10/splitted_0.jpeg)  |  ![Splitted Image](images/10/splitted_1.jpeg) |  ![Splitted Image](images/10/splitted_2.jpeg) | ![Splitted Image](images/10/splitted_3.jpeg) |![Splitted Image](images/10/splitted_4.jpeg)  |
|:-:|:-:|:-:|:-:|:-:|
| ![Splitted Image](images/10/splitted_5.jpeg) |  ![Splitted Image](images/10/splitted_6.jpeg) | ![Splitted Image](images/10/splitted_7.jpeg) |![Splitted Image](images/10/splitted_8.jpeg)|![Splitted Image](images/10/splitted_9.jpeg) |
|![Splitted Image](images/10/splitted_10.jpeg) |![Splitted Image](images/10/splitted_11.jpeg) |![Splitted Image](images/10/splitted_12.jpeg) |![Splitted Image](images/10/splitted_13.jpeg) |![Splitted Image](images/10/splitted_14.jpeg)|
|![Splitted Image](images/10/splitted_15.jpeg) |![Splitted Image](images/10/splitted_16.jpeg) |![Splitted Image](images/10/splitted_17.jpeg) |![Splitted Image](images/10/splitted_18.jpeg) |![Splitted Image](images/10/splitted_19.jpeg)|

#### Splitted images(150x150) with 50% overlap


| ![Splitted Image](images/50/splitted_0.jpeg)  |  ![Splitted Image](images/50/splitted_1.jpeg) |  ![Splitted Image](images/50/splitted_2.jpeg) | ![Splitted Image](images/50/splitted_3.jpeg)  | ![Splitted Image](images/50/splitted_4.jpeg)  |  ![Splitted Image](images/50/splitted_5.jpeg) |  ![Splitted Image](images/50/splitted_6.jpeg) |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| ![Splitted Image](images/50/splitted_7.jpeg)  |  ![Splitted Image](images/50/splitted_8.jpeg) |  ![Splitted Image](images/50/splitted_9.jpeg) | ![Splitted Image](images/50/splitted_10.jpeg)  | ![Splitted Image](images/50/splitted_11.jpeg)  |  ![Splitted Image](images/50/splitted_12.jpeg) |  ![Splitted Image](images/50/splitted_13.jpeg) |
| ![Splitted Image](images/50/splitted_14.jpeg)  |  ![Splitted Image](images/50/splitted_15.jpeg) |  ![Splitted Image](images/50/splitted_16.jpeg) | ![Splitted Image](images/50/splitted_17.jpeg)  | ![Splitted Image](images/50/splitted_18.jpeg)  |  ![Splitted Image](images/50/splitted_19.jpeg) |  ![Splitted Image](images/50/splitted_20.jpeg) |
| ![Splitted Image](images/50/splitted_21.jpeg)  |  ![Splitted Image](images/50/splitted_22.jpeg) |  ![Splitted Image](images/50/splitted_23.jpeg) | ![Splitted Image](images/50/splitted_24.jpeg)  | ![Splitted Image](images/50/splitted_25.jpeg)  |  ![Splitted Image](images/50/splitted_26.jpeg) |  ![Splitted Image](images/50/splitted_27.jpeg) |
| ![Splitted Image](images/50/splitted_28.jpeg)  |  ![Splitted Image](images/50/splitted_29.jpeg) |  ![Splitted Image](images/50/splitted_30.jpeg) | ![Splitted Image](images/50/splitted_31.jpeg)  | ![Splitted Image](images/50/splitted_32.jpeg)  |  ![Splitted Image](images/50/splitted_33.jpeg) |  ![Splitted Image](images/50/splitted_34.jpeg) |


### Image splitting can be used to
 - Get fixed size images from image of any size.
 - Generate partial fingerprints from any given fingerprint sample.
