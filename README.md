<h1> vgg_face_bollywood_celebrity_lookalike</h1>

<h2>In this project I created a streamlit app that takes picture of a person's face and the suggests which of the 100 bollywood celebrities he/she looks closest to. I used the weights from the vgg-16 model using transfer learning method. I trained more than 8,000 total pictures of those celebrities and store those matrices for those pictures.</h2> 


<h1>The basic function of the app is -</h1>

1.first convert the input picture into matrix form.

2.find the cosine distances between the input picture matrix and all the other matrix stored by the model.

3.find which particular celebrity picture matrix has the closest distance with the input picture matrix.

4.finally, display both the input picture and celebrity picture that has the minimum cosine distance with the input picture.


<h1>Some examples of the final app are given below</h1>

![test1](https://user-images.githubusercontent.com/59179489/189209607-2fa55776-62b9-4d24-870b-973e64a80d04.PNG)
![test2](https://user-images.githubusercontent.com/59179489/189209987-1fad55d6-2369-4992-856c-4559d6b1b30b.PNG)
![test3](https://user-images.githubusercontent.com/59179489/189210208-0f24803a-8029-4b9c-9a02-916e4c735f01.PNG)
![test4](https://user-images.githubusercontent.com/59179489/189210431-3d6b3529-06ea-45f9-87e8-e84aa640ae5b.PNG)
