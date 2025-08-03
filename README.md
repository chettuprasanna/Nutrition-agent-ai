<img width="1915" height="863" alt="image" src="https://github.com/user-attachments/assets/320b2ee7-7a33-462d-b5f5-1ae47db8fad4" />

# 🍽️ AI Nutrition Agent

This project leverages **AI and computer vision** to create a smart nutrition assistant that identifies food items from images and provides **dietary recommendations**. Designed using **IBM Watsonx.ai Studio**, it integrates deep learning models with **IBM Cloud Object Storage** for efficient image analysis and nutritional classification.

### 🔍 Problem Statement

With the increasing consumption of processed foods, many individuals lack awareness of their **nutritional choices**. This AI-powered assistant helps bridge that gap by:

- Identifying food items through uploaded images.  
- Offering **instant health suggestions** based on the food type.  
- Promoting healthier eating habits using **real-time dietary insights**.


### 🌟 Key Features

- **Image-based food recognition** using pre-trained deep learning models.  
- **Calorie and nutrition insights** for each detected item.  
- **Tailored health suggestions** based on the food type.  
- **Cloud-based storage and deployment** via IBM Watsonx.ai Studio.


 ### 🌟 Wow Factors

- **Integration with IBM Cloud Object Storage** for real-time image access.  
- **Supports multiple food types** in a single session (e.g., burger, pizza, salad).  
- **Instant visual results** and health advice with a clean user interface.  
- **Fully deployable** and adaptable for mobile or web applications.


### 🧠 AI Stack Used

- **Python**
- **Hugging Face Transformers** (`microsoft/resnet-50`)
- **IBM Watsonx.ai Studio**
- **IBM Cloud Object Storage (COS)**
- **PIL** & **Torch** for image processing and prediction



Sample Output:

<img width="1915" height="863" alt="Screenshot 2025-08-03 111431" src="https://github.com/user-attachments/assets/bf2c1381-299d-4e32-92c9-2d2a1891237b" />

<img width="1918" height="543" alt="Screenshot 2025-08-03 111447" src="https://github.com/user-attachments/assets/e771a891-9160-4c31-a9d5-ff3d78640ba9" />

<img width="1919" height="961" alt="Screenshot 2025-08-03 111509" src="https://github.com/user-attachments/assets/0713455c-850d-4871-82be-badb6212ebcf" />

<img width="1912" height="913" alt="Screenshot 2025-08-03 111526" src="https://github.com/user-attachments/assets/90482eac-5b8e-40cc-a4d9-4480e26c2e7b" />

<img width="1919" height="855" alt="Screenshot 2025-08-03 111540" src="https://github.com/user-attachments/assets/ae2f1e34-17a7-41ec-98c3-ac3338c9ecb2" />

<img width="1919" height="913" alt="Screenshot 2025-08-03 111558" src="https://github.com/user-attachments/assets/2c95eeca-5778-40ff-ad52-be4fde9fbefc" />


## ✅ How It Works

1. User uploads food image to IBM Cloud Object Storage.

2. The AI model processes the image to classify the food.

3. The model predicts the label and returns health suggestions.

4. The image and results are displayed back in the interface.
.













