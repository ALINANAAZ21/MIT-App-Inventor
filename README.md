# MIT-App-Inventor

# GSOC24 Final Submission
This gist summarizes the work I completed during the summer of 2024 as a contributor to the Google Summer of Code for the MIT App Inventor Foundation. 

## Project Summary
My work this summer as a contributor focused on implementing two new AI components in the MIT App Inventor development environment. These components were previously available only as extensions for Android. Additionally, I developed a common superclass for all AI components, compatible with both Android and iOS, to simplify the future development of other components. <br>
The project began with the development of a parent class, *BaseAiComponent*, and then proceeded with the development of the actual AI components, specifically an image classifier and an audio classifier, named PIC and PAC, respectively. Finally, I also updated the AI asset management system to ensure that assets are downloaded only when necessary. <br>
In the following paragraphs, you will find the PRs for each of these tasks. They are divided by component but include development in both Swift and Java

## Personal Image Classifier
The Personal Image Classifier (PIC) is an image classifier that works in both video and photo modes. The Android (Java) and iOS (Swift) code interacts with JavaScript code within the assets, which handles the actual classification. <br>


## Personal Audio Classifier
The Personal Audio Classifier (PAC) is an audio classifier that records your voice and then classifies it after converting it into a spectrogram. As with the PIC, the Java and Swift code focuses on communication with the JavaScript code. <br>


## Asset AI
This part of the project focused on improving AI asset management. By assets, I mean all the files used by the PIC and PAC, such as HTML and JavaScript files or Personal and Transfer models. The goal was to ensure that these assets are downloaded only when necessary, specifically when the app is in Companion mode. Otherwise, they are included during app compilation, so the user doesn't need to download them during the first run. <br>


## Personal notes
Participating in this year's Google Summer of Code has been a fantastic and enriching experience for me. Despite the various challenges encountered along the way, every moment spent was rewarding, allowing me to tackle problems with calmness and confidence. <br>
Working for the MIT App Inventor Foundation has significantly improved my technical skills and experience in this field, and I am grateful to the entire team for allowing me to be part of this amazing journey. <br>
