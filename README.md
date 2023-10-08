# Flight Price Prediction

## Overview

Flight Price Prediction is a web application developed using machine learning and Flask. It predicts the price of flight tickets based on various factors such as departure and arrival dates, source, destination, number of stopovers, and airline. The application utilizes a machine learning model trained on historical flight data to provide accurate price predictions for users.

## Technologies Used

- **Machine Learning**: The prediction model is built using machine learning algorithms. The project uses libraries like Scikit-Learn for data preprocessing, model training, and prediction.

- **Backend Framework**: Flask, a lightweight Python web framework, is used to handle server-side logic, manage routes, and communicate with the machine learning model.

- **Frontend Technologies**: HTML, CSS, and Bootstrap are used for creating the user interface. JavaScript is employed for client-side validation and dynamic content updates.

## How it Works

1. **User Input**: Users enter flight details, including departure and arrival dates, source, destination, number of stopovers, and preferred airline on the web interface.

2. **Validation**: Client-side validation ensures that users provide necessary information and selects appropriate options.

3. **Prediction**: Upon form submission, the input data is sent to the Flask server. The server uses the trained machine learning model to predict the flight ticket price based on the user's input.

4. **Display**: The predicted fare is displayed to the user in a pop-up modal window. Users can view the predicted price without navigating away from the form.

## File Structure

- **`app.py`**: The Flask application file that contains server-side logic, routes, and machine learning model integration.

- **`flight_rf.pkl`**: The trained machine learning model serialized using pickle for quick prediction without retraining.

- **`templates/`**: This directory contains HTML files for the user interface. `index.html` contains the form for user input, and it displays the predicted fare in a pop-up modal.

- **`static/css/`**: CSS files for styling the HTML elements. Bootstrap classes are also utilized for responsive design.

## How to Run

1. Clone the repository to your local machine.

2. Ensure you have Python and required libraries installed.

3. Run `pip install -r requirements.txt` to install necessary dependencies.

4. Execute `python app.py` in your terminal to start the Flask server.

5. Open a web browser and go to `http://localhost:5000` to access the application.

## Future Improvements

- **Enhanced User Experience**: Implement additional features such as date pickers, airport suggestions, and autofill to enhance the user experience.

- **Model Optimization**: Explore advanced machine learning techniques and hyperparameter tuning to improve the prediction accuracy.

- **Database Integration**: Integrate a database to store user queries and improve the application's functionality.

## Conclusion

Flight Price Prediction is a user-friendly web application that provides quick and accurate flight ticket price predictions. By leveraging machine learning and web technologies, the application offers a seamless experience for users seeking flight fare estimates. With continuous improvements, it has the potential to become a robust solution for travelers worldwide.
