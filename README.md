# Identifying-Professionals
IdenProf is a dataset containing images of identifiable professionals.
<hr>
<b>IdenProf</b> is a dataset of identifiable professionals, collected in order to ensure that machine learning systems can be trained
 to recognize professionals by their mode of dressing as humans can observe. This is part of our mission to train machine learning systems to perceive, understand and act accordingly in any environment they are deployed. <br><br>

  The professionals identifiable are: <br><br>

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

  This trained model was trained over **61 epochs** only, but it achieved **79%** accuracy on 2000 test images. You can see the prediction results on new images that were not part of the dataset in the **Prediction Results** section below. More experiments will enhance the accuracy of the model.
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
