# Project Name: [Identification of Different Medicinal Plants/Raw materials through Image Processing Using Machine Learning Algorithms]
# PS Code : [1343] 

## Team Name: VedaScan
- Team Members:
    Manya Trivedi
    Keya Shah
    Naqibahmed Kadri
    Suraj Menon 
    Zakariya Mansuri 
    Faisal Choriwala

- Contact Email: manyatrivedi2612@gmail.com


## Project Overview 🚀
The purpose is to develop a software based solution that enables accurate identification of various medicinal plants and raw materials using machine learning and image processing techniques.The primary goal is to create a website that can analyze images of these plants and materials, extract relevant features or characteristics, and classify them correctly.
What problem does it solve? What's its significance? This section should provide an exciting introduction to our project.

## Tech Stack 💻

Here are the technologies and tools we used to build our AI solution:

example :

* **HTML** <img src="https://img.shields.io/badge/HTML5-E34F2C?style=for-the-badge&logo=html5" alt="HTML5">
* **CSS** <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3" alt="CSS3">
* **Python** <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python" alt="Python">
* **PyTorch** <img src="https://img.shields.io/badge/Pytorch-3776AB?style=for-the-badge&logo=python" alt="Python">
* **TensorBoard** <img src="https://img.shields.io/badge/TensorBoard-3776AB?style=for-the-badge&logo=python" alt="Python">
* [More technologies/tools used]


## Project Features and Functionality ✨
PROJECT FEATURES
1. Image Recognition: The system will utilize state-of-the-art machine learning models to recognize medicinal plants and raw materials from images.

2. Database Integration: A comprehensive database of medicinal plants and their characteristics will be integrated into the system to aid in accurate identification.

3. User-Friendly Website: A user-friendly website will be developed, allowing users to easily upload images for analysis.

4. Real-time Analysis: The system will provide real-time analysis and generate detailed reports on the identified plants, including their botanical characteristics.

5. Accuracy Improvement: Continuous learning and feedback mechanisms will be implemented to enhance the system's accuracy over time.

FUNCTIONALITY
- We identify the uploaded image/video of ayurvedic medicinal leaf.
- It detects the quality of the detected ayurvedic leaf.
- Properties and information regarding the given ayurvedic plant is show in the UI.
- If the captured image/ video is not a close up shot, identification of the plant will be shown instead of leaf.

## How It Works 🛠️
- 2 models are used: one for identifying leaf and other for to check whether defect exists or not.
- Image is passed through first yolo model which identifies the leaf then the same image is passed through the second yolo model .
- The bounding box area of the second and first models are compared to obtain quality index.
- Once the leaf is identified, information regarding that particular leaf is provided in the UI. This is achieved through a LLM model.


## Challenges and Solutions 🧠
- The biggest challenge was to determine the quality of the leaf since there was no predefined logic/model.
We overcame it through:
We decided to use another model which specifically detects if defect exists or not.
The area of bounding box obtained is then compared to the area of the bounding box of the leaf.
If the value of the areas obtained are closer to each other then the quality of the leaf is bad.
We can convert the same in percentage to get a better understanding of the quality.

## Future Enhancements 🚧
- By using the combination of the detected medicinal plant/raw material and their attributes and properties it suggests the authentic ayurvedic medicines.

## Screenshots and Demos 📸
![img](image.png)
![img2](image-1.png)


## Get In Touch! 📬


| Team Member | LinkedIn | Kaggle | Email |
|---|---|---|---|
| Naqibahmed Kadri | [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/naqibahmed-kadri/) | [![Kaggle](https://img.shields.io/badge/Kaggle-%2320B2AA.svg?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/nakibahmedkadri) | [naqibahmedkadri@gmail.com](mailto:naqibahmedkadri@gmail.com) |



---


[Add any additional sections or content specific to our project here.]
