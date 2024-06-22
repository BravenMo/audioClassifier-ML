# AudioClassifier-ML
This repository hosts a machine learning project designed to classify and identify various audio inputs. The project includes the following key components:

- **Data Preprocessing:** Methods for loading and processing audio files using librosa, and extracting meaningful features like Mel-frequency cepstral coefficients (MFCCs).
- **Feature Extraction:** Implementation of a feature extractor function to compute MFCC features from audio data.
- **Model Training:** Training various classifiers including Logistic Regression, Decision Tree, Random Forest, and XGBoost to identify audio classes. The project demonstrates the use of these models and compares their performance.
- **Evaluation:** Comprehensive evaluation of model performance using metrics such as accuracy. The repository also includes an ensemble method to improve classification accuracy.
- **Deployment:** Scripts and tools for deploying the trained models to real-time audio classification systems.
- **Documentation:** Detailed documentation and interactive Jupyter notebooks to facilitate understanding and replication of the project results.

## Project Structure
### Data Loading and Preprocessing:
- Loading metadata and audio files from the UrbanSound8K dataset.
- Displaying audio waveforms using librosa and IPython.display.

### Feature Extraction:
- Extracting MFCC features from audio files.

### Model Training and Evaluation:
- Training Logistic Regression, Decision Tree, Random Forest, and XGBoost classifiers.
- Evaluating models on test data and comparing their accuracy.
- Implementing an ensemble method to enhance classification accuracy.

### Scripts and Notebooks:
- Detailed scripts for each stage of the process, from data loading to model evaluation.
- Jupyter notebooks for interactive exploration and visualization of results.

![image](https://github.com/BravenMo/AudioClassifier-ML/assets/91548058/b7850dec-84a8-48f4-b3b8-19fd101d44d1)
