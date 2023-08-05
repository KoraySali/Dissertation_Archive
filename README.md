# Dissertation Archive - Wildfire Detection
This Github repository will be linked to Google Colaboratory, Jupyter Notebook and PyCharm for the creation of a neural network for image detection of wildfires.


# Website goal
``The model will utilise a webpage for high-altitude imagery to identify fire with the hops of pin point the object in the image.``

# External Camera use
``The model will also utilise external cameras to take input images and identify any possible fire or smoke in the images in order to leverage the exisiting low-tech CCTV surveillance systems in place.``

# Main Findings
The main finding of this investigation was our CNN-SVM ensemble produced an accuracy of 95% across 2,400 test images. The pre-existing CNN architectures used were mostly high performing, some even achieving well over 99% accuracy.

![alt text](https://github.com/KoraySali/Dissertation_Archive/blob/c42a8902444419737c173227298aa029a3c68092/ML%20Ensembled%20Test%20Accuracies.png)

Throughout completion of this project a variety of graphs, tables and other visualisations were used to better percieve the ability to identify wildfires. It has become apparent throughout that not only is it possible to identify wildfires from low altitude imagery, such as CCTV camera imagery, mobile phone images and camera imagery, but it is also possible to identify wildfires from high-altitude imagery like satellite imagery.

The applicability of this model to all scenarios means small and/or early wildfires can be dealt with quickly, therefore preventing the spread of damage and reducing costs. The model is also able to identify smoke as well as regarding images with neither smoke or fire as, "No Fire or Smoke."

![alt text](https://github.com/KoraySali/Dissertation_Archive/blob/ce320e158786d268ef4100d587b7e530dff443b1/Validation%20Accuracy.png)

## External Camera Utility

To demonstrate the ability of CNN-based models further, I wanted to take snapshots from a live feed of my computers webcam and process these images to be identified by the model. This can be used to leverage current low-level technology CCTV systems, which most wildfire teams tend to use.

![alt text]()

## Website Front-end

This was further paired with a front-end website so wildfire surveillance teams can input macro-imagery into the CNN model at any given time and recieve an output of what the image contains. This was particularly useful if the fire is unobservable or unobvious to the human eye.

![alt text]()
