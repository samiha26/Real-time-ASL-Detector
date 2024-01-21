# Sign-Language-Detection---Deep-Learning
Sign Language Label Reference
https://docs.google.com/document/d/1YCC71Y6zXfjPzH4pjUPxE4mtqk8SJ2He_2RDMiTyjuU/edit?usp=sharing 

**Step to modify this project**
1. Run app.py (Make all the packages installed and the cam works fine.)
2. Test any signs that have trained (based on the keypoint_classifier_label.csv)
3. To add some new input labels, toggle "k" for input collection mode
4. Once you have prepared and shown your desired input label to the cam, toggle the order number (e.g. 0-9) of the desired input labels continuously for different coordinates of the desired input labels.
5. Remember to add the name of the input label in the keypoint_classifier_label.csv
6. After the input labels are done, then start training the model (keypoint_classfication.ipynb).
7. Remember to change NUM_OF_CLASSES = 18 when adding more of the new input labels.
8. Run and train the model.
9. Check when the epochs stop running and the accuracy of the model before executing the app.py.
10. May modify the network, maybe a deeper network, and add more hidden layers to the network. 
