# Identifying-Professionals
IdenProf is a dataset containing images of identifiable professionals.
<hr>
<b>IdenProf</b> is a dataset of identifiable professionals, collected in order to ensure that machine learning systems can be trained
 to recognize professionals by their mode of dressing as humans can observe. This is part of our mission to train machine learning systems to perceive, understand and act accordingly in any environment they are deployed. <br><br>

  The professions identifiable are: <br><br>

  - <b> Chef </b> <br>
  - <b> Doctor </b> <br>
  - <b> Engineer </b> <br>
  - <b> Farmer </b> <br>
  - <b> Firefighter </b> <br>
  - <b> Judge </b> <br>
  - <b> Mechanic </b> <br>
  - <b> Pilot </b> <br>
  - <b> Police </b> <br>
  - <b> Waiter </b> <br> <br>

  There are <b>1,100 images</b> for each category, with <b>900 images for trainings </b> and <b>200 images for testing</b> . We are working on adding more
   categories in the future and will continue to improve the dataset.
  <br><br> <br> <br>

  <b>>>> DOWNLOAD, TRAINING AND PREDICTION: </b> <br><br>
 The <b>IdenProf</b> dataset is provided for download in the <b>release</b> section of this repository.
 You can download the dataset via this <a href="https://github.com/OlafenwaMoses/IdenProf/releases/" >link</a> . <br><br>

 We have also provided a python codebase to download the images, train <b>ResNet50</b> on the images
  and perform prediction using a pretrained model (also using <b>ResNet50</b>) provided in the release section of this repository.
  The python codebase is contained in the <b><a href="idenprof.py" >idenprof.py</a></b> file and the model class labels for prediction is also provided the 
  <b><a href="idenprof_model_class.json" >idenprof_model_class.json</a></b>. The pretrained <b>ResNet50</b> model is available for download via this 
  <b><a href="https://github.com/OlafenwaMoses/IdenProf/releases/download/v1.0/idenprof_061-0.7933.h5" >link</a></b>. This pre-trained model was trained over **61 epochs** only, but it achieved **79%** accuracy on 2000 test images. You can see the prediction results on new images that were not part of the dataset in the **Prediction Results** section below. More experiments will enhance the accuracy of the model.
<br>
Running the experiment or prediction requires that you have **Tensorflow**, **Numpy** and **Keras** installed.
<br><br> <br> <br>

<b>>>> Prediction Results</b> <br><br>
  <img src="test-images/1.jpg" />
<pre>
chef  :  99.90828037261963
waiter  :  0.0905417778994888
doctor  :  0.0011116820132883731
</pre>

<hr>
<br>

<img src="test-images/2.jpg" />
<pre>
firefighter  :  80.1691472530365
police  :  19.79282945394516
engineer  :  0.03719799569807947
</pre>

<hr>
<br>

<img src="test-images/6.jpg" />
<pre>
pilot  :  99.75990653038025
mechanic  :  0.21259593777358532
police  :  0.024273521557915956
</pre>

<hr>
<br>
