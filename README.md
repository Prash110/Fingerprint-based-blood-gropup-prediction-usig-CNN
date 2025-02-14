# Blood-Group-Prediction-from-Fingerprints-Using-CNN

## :information_source: Need Help or More Details?

If you have any **questions**, need **project reports** or **PowerPoint presentations**, or require the **complete code** and **setup instructions**, don't hesitate to contact me:

📧 **Email:** [karthikgr1908@gmail.com](mailto:karthikgr1908@gmail.com)
🔗 **LinkedIn:** [Karthik G](https://www.linkedin.com/in/karthik-g-04b016210/) 


## :computer: System Architecture

The system architecture is designed to predict blood groups from fingerprint images using deep learning techniques. The architecture includes the following components:

![image](https://github.com/user-attachments/assets/bbaadca1-9d6c-4b6a-80fa-a07a1bbf399f)

## :arrow_right: Flow Chart

Here’s the general flow of the system:

![image](https://github.com/user-attachments/assets/53e6dbcb-c3ae-4a90-ba45-78e99c60f769)

# Setup Instructions
Follow the steps below to set up the project environment:

## :wrench: Prerequisites

Before setting up the project, ensure that you have the following installed on your system:

### Software Requirements:
- **Python 3.x**: Required for running the project and deep learning model.
- **Anaconda**: For managing environments and dependencies (can be installed via [Anaconda website](https://www.anaconda.com/products/individual)).
- **Git**: For cloning the repository (can be installed via [Git website](https://git-scm.com/downloads)).
- **Visual Studio Code** or **PyCharm**: Recommended text editors/IDEs for code editing.

## Setup Instructions

### 1. Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/Karthikg1908/Blood-Group-Prediction-from-Fingerprints-Using-CNN.git
cd Blood-Group-Prediction-from-Fingerprints-Using-CNN
```

### 2. Create and Activate a Virtual Environment
It's recommended to use a virtual environment for managing dependencies

For Windows:
```
python -m venv venv
venv\Scripts\activate
```

For macOS/Linux:
```
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies Using Conda
Install necessary dependencies using Conda:

```
conda install -c conda-forge keras
conda install -c anaconda scikit-learn
conda install -c conda-forge opencv
conda install -c anaconda scikit-image
conda install -c anaconda flask
conda install numpy
conda install pillow
```

### 4. Install Additional Dependencies Using pip
After installing the Conda dependencies, install the remaining packages with pip:

```
pip install tensorflow
pip install pandas
pip install werkzeug==2.3.7
pip install flask torch torchvision torchaudio pillow werkzeug flask-wtf wtforms
```

### 5. Run the Flask Application
Run the Flask application with the following command:

```
python app.py
```

### 6 Access the Web Application
Open a web browser and navigate to http://127.0.0.1:5000/ to use the fingerprint blood group prediction system.


## :handshake: Contributing

We welcome contributions to improve the project. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make the changes, and ensure to test them thoroughly.
4. Submit a pull request with a clear description of the changes.

For any issues or bugs, feel free to open an issue in the GitHub repository.


## :rocket: Future Improvements

- Improve model accuracy by experimenting with deeper architectures or other deep learning models (e.g., ResNet, Inception).
- Add support for real-time fingerprint scanning and blood group prediction.
- Extend the project to classify more characteristics from fingerprints, such as age or gender.


## :information_source: Need Help or More Details?

If you have any **questions**, need **project reports** or **PowerPoint presentations**, or require the **complete code** and **setup instructions**, don't hesitate to contact me:

📧 **Email:** [karthikgr1908@gmail.com](mailto:karthikgr1908@gmail.com)
🔗 **LinkedIn:** [Karthik G](https://www.linkedin.com/in/karthik-g-04b016210/) 
