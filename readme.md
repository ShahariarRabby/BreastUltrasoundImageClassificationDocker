
# Breast Ultrasound Image Classification

## Introduction

The Breast Ultrasound Image Classification project is a web-based application designed to classify breast ultrasound images into benign, malignant, or normal categories using a machine learning model. This tool aims to support early detection and preliminary screening of breast cancer, enhancing diagnostic capabilities for healthcare professionals.

## Getting Started

### Clone the Repository

First, clone the repository from GitHub:

```bash
git clone https://github.com/ShahariarRabby/BreastUltrasoundImageClassificationDocker.git
cd BreastUltrasoundImageClassificationDocker
```

### Download Model Weights

Download the model weights from [Google Drive](https://drive.google.com/xxx) and place the `best_model_multi.h5` file in the root directory of the project.

### Running with Docker

1. **Build the Docker Image**

   ```bash
   docker build -t flaskapp .
   ```

2. **Run the Docker Container**

   ```bash
   docker run -p 5000:5000 flaskapp
   ```

   The application will be available at `http://localhost:5000`.

### Running Without Docker

1. **Setup the Environment**

   Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install Dependencies**

   Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask Application**

   Start the Flask server:

   ```bash
   python app.py
   ```

   The application will be available at `http://localhost:5000`.
## Example Images

Here are some example images used for classification:

- **Benign**: ![Benign](static/sample_benign.png)
- **Malignant**: ![Malignant](static/sample_malignant.png)
- **Normal**: ![Normal](static/sample_normal.png)
- 
## Screenshots

Here are some screenshots of the application:

- ![Screenshot 1](screenshots/screenshots1.png)
- ![Screenshot 2](screenshots/screenshots2.png)
- ![Screenshot 3](screenshots/screenshots3.png)
- ![Screenshot 4](screenshots/screenshots4.png)
- ![Screenshot 5](screenshots/screenshots5.png)

## Demonstration Video

Watch the demonstration video [here](project_demonstration.mp4) to see the application in action.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

