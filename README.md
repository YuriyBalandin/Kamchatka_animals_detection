# WildHack hackathon solution - a case from the Kronotsky Reserve on recognizing animals from camera traps.

The problem that needed to be solved was to use artificial intelligence to distinguish between photos that lack animals or poor quality frames. After that, it was necessary to detect the main animals in pictures or videos from camera traps.

The solution is based on the use of the yolov5 model trained on labeled data, the user interface is implemented using streamlit.

For start:
The main.py file must be run with the streamlit run main.py command

The models folder contains the weights of the trained model.
Notebooks with model development are in the notebooks folder.
