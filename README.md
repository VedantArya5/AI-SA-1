# AI-SA-1
The **Gesture Sign Language Translator** uses Google Teachable Machine to recognize and translate American Sign Language (ASL) gestures into text in real-time. That makes communication for deaf individuals and the everyday spaces more accessible-a digital space, as well as the traditional physical ones.

**google teachable link**: https://teachablemachine.withgoogle.com/models/[...]

## 1. Data Collection and Preparation

### Data Collection Process
While building our **Basic Sign Language Translator**, we captured pictures of hand-related gestures depicting everyday phrases in **American Sign Language (ASL)**, like "Hello," "Sorry," and "Nice to meet you." Recording tens of thousands of iterations of such gestures by our webcam (recording them from diverse angles and lighting conditions), we ensure that our data is diversely represented.

### Effect of Diversified Data
This diversity of the data set - hand movements, lighting, and backgrounds-it carried with it added the power of the model in terms of accuracy and its robustness for real-time performance. It helped generalize well cross-cutting over different users and environments.

---

## 2. Google's Teachable Machine

Google's **Teachable Machine** was used for-

Capturing Data: A webcam was used to capture live images of simple ASL phrases like "Hello," "Sorry," etc, each labeled accordingly.
- **Train the Model:** The model is trained after the collection of data through the use of the platform, during which it categorized the data into categories for all phrases.
- **Test and Export:** Test the recognition for the model in real-time after training and export the model for continued use or integration.
---
---
## 3. Features and Functionalities
### Key Features:
- **Phrase Recognition:** This model recognizes unique hand gestures meant for common phrases the user is aware of in ASL, like "Hello," "Sorry," and "Nice to meet you."
- **Live Translation:** Users will make gestures in front of the camera, and the model will instantly translate what they write.
- **Multi-Angle Detection:** This model is designed to detect gestures from a few angles in different views, which make the model usable in various aspects.
### Features:
- **Webcam Input:** Reads real-time hand gestures.
- **Interactive Text Output:** Shows the translated text according to the recognized ASL gesture.
- **Easy-to-Use Interface:** The model is user-friendly with no technical knowledge required to use it.

---

## 4. Evaluation Methods

- **Accuracy Testing:** Tested the model to perform accurate classification of each gesture in varying lighting and angle conditions.
- **User Testing:** Done by multiple users who performed the same gestures, making sure the model works well with varying hand shapes and sizes.
- **Confusion Matrix:** A confusion matrix was used to establish which, if any phrases were misclassified and therefore a goldmine for tweaking the dataset and enhancing performance.
- **Cross-Validation:** The cross-validation methods ensured that the predictions from a model did not overfit on certain examples and that its predictions were consistent.

---

## 5. Real-World Applications

### Better Communication
This tool would help non-signers and ASL learners communicate with the deaf and hard-of-hearing community. Its utilization is perfectly suited for informal and formal settings in which it would be pertinent to hear some phrases like "Hello" or "Sorry".

### Learning Tool
The translator also could be a useful tool for ASL learners by providing real-time feedback on their gestures in regard to their commonly used sign phrases, which will enable users to practice and perfect their signs.

Device Integration
It can be integrated into either mobile or desktop applications in which users can easily communicate using simple ASL phrases in public settings, at school, or in client services.
---

Conclusion
The **Basic Sign Language Translator** is a user-friendly ASL translation tool that bridges many communication gaps by converting simple phrases into real time. Made using Google Teachable Machine, this project demonstrates exactly what technology does for an increased inclusion and accessibility to communicate.
