# Smart-Crop-Recommendation-System
Crop Recommendation system using Blended XGBoost and SVM machine learning models
## Features
- Predicts the most suitable crop to grow based on soil and environmental conditions.
- Utilizes a hybrid approach combining XGBoost and SVM for accurate predictions.
- Easy-to-use interface for farmers and agricultural experts.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Akhil-peram/Smart-Crop-Recommendation-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Smart-Crop-Recommendation-System
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare your dataset with the required features (e.g., soil type, temperature, humidity).
2. Run the main script to get crop recommendations:
    ```bash
    python app.py
    ```
3. Follow the prompts to input your data and receive recommendations.

## Dataset
The system uses a dataset containing information about soil conditions, weather parameters, and crop yields. Ensure your dataset is formatted correctly before use.


## Starting the Project
After installing the requirements, click "Run". Then, at the bottom, click on the running local server.
![start](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/9a4a5f3c424300ae525258ef7c30225530db27b8/imgs/start.png)


## This is our home page:

![homepage](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/65190f6d7d2c6ba87a66d148c4ab5c13f0818da1/imgs/homepage.png)
![homepage2](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/ffbee75c57e04f303c119e1f9038e9894cee536d/imgs/trynow.png)

## User Input
The user enters the Environmental details like  **Nitrogen, Phosphorous, Posttasium, pH** of soil and submit.

![Screenshot (132)](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/65190f6d7d2c6ba87a66d148c4ab5c13f0818da1/imgs/prediction.png)

## Results of the crop recommendation
These will be results of the crop recommendation, we are recommendting top five crops that can be grown on that soil which have the specitic attributes.

![crop recommended](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/78265fdafc77effd8927faa923a6c4d3aa5269c7/imgs/croppredicted.png)
![crop details](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/382a9883beea3374f455cf4858194f9bd7aa4b11/imgs/Screenshot%20(31).png)

## Details of 22 Crops
We have scraped the data fron the official website, which consists details , how each crop can be grown , what are the fertilizers has to be used, what must be the soil fertility and duration of the crop.

![Details](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/de5477befca627e216661ded59ed0e80eac23cb8/imgs/Screenshot%20(29).png)


## Model Performance based on Accuracy and Sensitivity
### *Correlation Matrix for the Features*
![correlation matrix](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/0165ab7376af8303b5f4ae9d5ae6c418439c8f4a/imgs/correlation.png)

### *Performance of different models*
![performance](https://github.com/Akhil-peram/Smart-Crop-Recommendation-System/blob/c8ee2759ce7820db2a36e0645088b3b6f7543525/imgs/output.png)


### NOTE: Use Pycharm for Running the Project , for better management of dependencies

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
