# Food Classifier

A web application that classifies food images into different categories.

https://food-classifier-two.vercel.app/

## Overview

This project consists of two main components:

1. **Web Interface**: A clean, modern UI for uploading food images and displaying predictions
2. **Model**: A trained TensorFlow model for food image classification

## Features

- Drag and drop image upload
- Image preview
- Food category prediction
- Confidence score display
- Responsive design for all devices

## How to Use

1. Open the `food-classifier-app/food-classifier.html` file in any web browser
2. Upload a food image by clicking on the upload area or dragging and dropping
3. Click the "Predict Food Category" button
4. View the predicted food category and confidence level
5. Click "Predict Again" to try with another image

## Food Categories

The classifier can identify 30 different food categories:

- Apple Pie
- Beef Tartare
- Cannoli
- Churros
- Cup Cakes
- Deviled Eggs
- Donuts
- Dumplings
- Edamame
- French Fries
- Fried Rice
- Garlic Bread
- Gnocchi
- Greek Salad
- Gyoza
- Hamburger
- Hot and Sour Soup
- Hot Dog
- Ice Cream
- Mussels
- Onion Rings
- Oysters
- Pancakes
- Pizza
- Ramen
- Samosa
- Sashimi
- Spring Rolls
- Sushi
- Waffles

## Technical Details

The current implementation uses a client-side approach for demonstration purposes. For a production environment, the application would be connected to a server that:

1. Loads the TensorFlow model
2. Processes uploaded images
3. Returns real predictions based on the model

## Future Improvements

- Server integration with the trained model
- Image preprocessing enhancements
- Multiple model support
- User history tracking
- Mobile app version

## License

MIT License
