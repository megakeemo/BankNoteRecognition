# Bank Note Recognition
This project seeks to develop a proof of concept prototype for an automated system to be used by the International Commercial Bank (ICB), that is able to classify two different types of Jamaican bank notes - namely the one thousand dollar (J$1000.00) and five hundred dollar (J$500.00) notes. The prototype was developed using images of the bank note collected from digital photographs or found on the internet, that were then used to train a neural network model to classify other images. This model is intended to be further trained to recognise other Jamaican bank notes in future iterations of the project. 

# The Deployment Notebook
The model was deployed using the Voila addon for Jupyter Notebooks. Voila outputs the notebook in HTML, meaning that the system is able to be deployed on a web server and accessible to the entire world.

The deployment notebook contains two buttons, the first for uploading an image, and the second for predicting the denomination of the bank note. The system will predict whether the uploaded image is JMD $500, $1,000 or none of the two.

