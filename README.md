# Housing Price Prediction 🏠

Ever wondered what actually makes a house expensive? I built this machine learning model to find out! It predicts housing prices based on different features like size, number of bedrooms, and more.

## What This Does

I trained a linear regression model on housing data to predict prices. Turns out the model can explain about 64% of what makes a house cost what it does (R² = 0.636). Not perfect, but pretty decent for a straightforward approach!

## What I Learned

After running the analysis, here's what affects house prices the most:

1. **Area** (square footage) - This is BY FAR the biggest factor. Makes sense, right?
2. **Bedrooms** - More bedrooms = higher price
3. **Bathrooms** - Same deal
4. **Parking spots** - People will pay for parking
5. **Stories** (floors) - Surprisingly, the least important

The visualizations really show this - the area scatter plot has a clear upward trend, while things like the number of stories are all over the place.

## The Data

The model looks at these features:
- Area (size in square feet)
- Number of bedrooms
- Number of bathrooms  
- Number of stories
- Parking spaces
- Plus some yes/no features like: main road access, guestroom, basement, hot water heating, AC, and if it's in a preferred area

I removed the "furnishing status" column because it wasn't adding much value to the predictions.

## Tools I Used

- **Python** for everything
- **Pandas** for data handling
- **Scikit-learn** for the machine learning
- **Matplotlib & Seaborn** for visualizations
- **Jupyter Notebook** to keep it all organized
