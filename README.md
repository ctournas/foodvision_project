# FoodVision Big: PyTorch Model Deployment

FoodVision Big is an advanced image classification project built using PyTorch. This repository showcases the end-to-end workflow of creating, training, and deploying a machine learning model for food image classification. 

The project leverages a pre-trained EfficientNet B2 model fine-tuned on the Food101 dataset to achieve high accuracy. It also includes steps to turn the trained model into a deployable application.

| **Features** | **Description** |
|--------------|-----------------|
| **EfficientNet B2 Fine-Tuning** | Using transfer learning for efficient and accurate image classification. |
| **Custom Training Pipeline** | Implementation of a modular training process for flexibility and scalability. |
| **Model Deployment** | Structured as a web app for real-world testing and interaction. |
| **Pre-trained Model Management** | Save, load, and evaluate the trained model efficiently. |
| **App Structure** | Guidelines and scripts to deploy the model as a web application. |

## Repository Structure
| **Directory/File**                  | **Description** |
|-------------------------------------|-----------------|
| `models/`                           | Directory for saving trained models. |
| `demos/foodvision_big/`             | Application files for deployment. |
| `09_pretrained_effnetb2_feature_extractor_food101_20_percent.pth` | Pre-trained model weights. |
| `app.py`                            | Main app script for deployment. |
| `class_names.txt`                   | Class names for Food101 dataset. |
| `examples/`                         | Example images for testing. |
| `model.py`                          | Model definition and architecture. |
| `requirements.txt`                  | Dependencies for the application. |

## Key Objectives
| **Objective** | **Details** |
|---------------|-------------|
| Train a pre-trained EfficientNet B2 model | Fine-tune for the Food101 dataset. |
| Save and load the trained model efficiently | Ensure model compatibility across platforms. |
| Deploy the model as a web application | Allow real-world usability and interaction. |
| Evaluate and optimize the model size | Enhance deployment performance. |

## How to Use
1. Clone this repository:  
  ```bash
  git clone https://github.com/yourusername/foodvision-big.git
  ```

2. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```

3. Train the model or load the pre-trained weights.
4. Deploy the app locally:
  ```
  python app.py
  ```

## License
This project is licensed under the MIT License.


