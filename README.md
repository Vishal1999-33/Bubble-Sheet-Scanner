# About

The main objective of this project was to build a computer vision system using Python and OpenCV that can read and grade bubble sheet tests.

Below I have included a screenshot of sheet after applying edge detection:-

![omr_edged](https://user-images.githubusercontent.com/54469035/81554305-2bfad580-93a4-11ea-807b-fc2f3cfd60f1.jpg)

Below I have included an example image that demonstrates the *__docCnt__*  variable being drawn on the original image:

![omr_found_exam](https://user-images.githubusercontent.com/54469035/81554437-69f7f980-93a4-11ea-8cb5-e511e3bc581f.jpg)

After applying Otsu’s thresholding method, our exam is now a binary image:

![omr_thresh](https://user-images.githubusercontent.com/54469035/81554521-96137a80-93a4-11ea-96ef-892f7b88afbe.jpg)

Below I have included a screenshot that has drawn the output of *__questionCnts__*  on our image:

![omr_finding_bubbles](https://user-images.githubusercontent.com/54469035/81554626-c22efb80-93a4-11ea-815b-9bbf94a4f15a.jpg)

A screenshot below that depicts each row of questions as a separate color:

![omr_bubble_rows](https://user-images.githubusercontent.com/54469035/81554736-f2769a00-93a4-11ea-90a4-02f5ea735b1c.jpg)

Below I have included an example of creating and applying a mask to each bubble associated with a question:

![omr_mask](https://user-images.githubusercontent.com/54469035/81554822-15a14980-93a5-11ea-86b3-38f21afc2143.gif)

