# EcoSort-A-Computer-Vision-Pipeline-for-Automated-Waste-Sorting-Management

# EcoSort: AI-Powered Waste Sorting ♻️

This project explores the use of Computer Vision to automatically classify waste into **Organic** 🍎 and **Reusable** (Recyclable) 🚮 categories.

The primary goal is to build and compare deep learning models that can automate waste sorting, reducing the need for manual human labor and improving the efficiency of waste management. This project compares two leading architectures, **VGG16** and **ResNet50**, to find the most effective model for the task.

**The optimized model achieved 91.70% accuracy!** 🏆

## 🎯 The Problem

Manual waste sorting is a slow, expensive, and often unpleasant task. As waste production increases, automating this process is essential for efficient recycling and environmental management. This project aims to create a "smart-sorting" solution using AI.

## 🛠️ How It Works

This project uses **Transfer Learning** to build a powerful image classifier.

1.  **Dataset:** The models were trained on the **[Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)**, which contains images of organic and recyclable items.
2.  **Data Preprocessing:** Images were loaded, resized, and augmented (flipped, rotated, zoomed) using TensorFlow's `ImageDataGenerator` to create a robust training set.
3.  **Model Benchmarking:** Two pre-trained CNN architectures were compared:
    * **VGG16**
    * **ResNet50**
4.  **Training:** Both models were fine-tuned on the waste dataset, and their performance was carefully evaluated.

## 📊 Results & Conclusion

Both models produced interesting and promising results, but one was a clear winner.

* **VGG16:** [Enter VGG16 Accuracy, e.g., XX.X%]
* **ResNet50:** **91.70% Accuracy**

The **ResNet50** model demonstrated a superior ability to distinguish between the two waste types, making it the recommended architecture for this solution.

This project successfully proves that Computer Vision can be a highly effective tool for automating waste distribution. A model like this could be deployed in smart bins or on sorting conveyor belts to **significantly reduce human effort** and make recycling more efficient.

## 🚀 How to Run This Project

You can easily clone and run this project to test the models yourself.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```
2.  **Install dependencies:**
    ```sh
    pip install tensorflow numpy matplotlib
    ```
3.  **Download the Dataset:**
    * Download the dataset from [Kaggle](https://www.kaggle.com/datasets/techsash/waste-classification-data).
    * Unzip it and place it in the project's root directory (or update the path in the notebook).
4.  **Run the Notebook:**
    * Open the `.ipynb` file in Google Colab or Jupyter Notebook.
    * Run the cells to train the models and see the results!
