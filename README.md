# EYEAM Machine Learning Repository

A Repository for Machine Learning Part Development Team of EYEAM Project :
- Yosua Sintikhe Lukas (M2320G2795)
- Valentino Rizky (M2014K1366)

Description
--
EYEAM:  Endangered Animal the idea off Our App to Educate anyone to carrying for endangered species in the world. We know that wildlife existence is being threatened. If it is not taken care of, the global population and environment will become unbalanced and resulting in even worse environmental damage. The lack of education about wildlife causes humans not to understand that certain animals are endangered, especially when doing land acquisition. Even with the existence of worldwide law and regulations, humans are still a threat to wildlife populations, be it intentionally for hunting (commercial) purposes or unintentionally (destroying habitat for living areas). From these problem, we took the initiative to build this educational application for anyone. The features contained in this application, including:

- Find the endangered animal using feature in the application by species name.
- The application can detect the animal from camera features and show the information immediately.

Classify the Images
--
For Classify the Images, we compiling 300 images for self-made dataset (Among them are 6 classes with 50 pictures). Then we proceeds to do data splitting for training-test data and pre-processing. Baseline model is made, then enhanced using experiments with image augmentation and tuning the parameter with transfer learning (InceptionV3 and MobileNetV2). The best model, transfer learning InceptionV3, is chosen and exported to .h5 format for deployment.

Dataset
--
We decided to build our own dataset because we didn't find the right dataset for our project. We crawl and search data from many sources and make it into a single dataset which you can view in the rigt here <a href="https://github.com/EYEAM-Bangkit/Machine-Learning/tree/main/EYEAM%20Image%20Data">here</a>
