# Traductor de Señas
**Integrantes**
- William Palomino
- Henry Peña
- Diego Medina


**Universidad Indsutrial De Santander** </br>
**Ingenieria de sistemas**</br>
**2019**</br>
<p align="center"><img src="http://garza.uis.edu.co/idayregreso/images/logoUIS.jpg" width="342" heigth="166"></p>

# Introduccion
El planteamiento del proyecto consiste en crear un traductor de señas utilizando algortimos de clasificacion de imágenes el cual permita la comunicacion entre una persona que maneja esta lengua con otra que desconozca este lenguaje.

Para esto utilizaremos un dataset en formato MNIST ya que facilita el procesamiento de los datos, el dataset cuenta con 27,455 casos para entrenar y 7172 casos para probar, dicho dataset contiene imagenes como las siguientes:
<p align="center"><img src="https://storage.googleapis.com/kaggle-datasets/3258/5337/amer_sign2.png?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1550815074&Signature=JIexSnL%2FvE4T3b%2FaF2MVpqt%2FwegHST%2BJHTbtZAi1fv97WvLV7SHFxc1ZeYV%2BY4lza15DAugkc7K4eOz9ekIMo%2FuUNyTilL4X8x0kHvunjus8LU2DCGviyD1Qc1SSn3MVwHj%2FUaqaPgft5i3qyrSxOIZL3fngFvGgeaQbqIk4naO%2BGdjxs00C4kjR3wdMrJ%2BzPP%2FeYnwTS1%2FzzQbae9GoWuUWrsn4ZyxznzdYKsJ6bX%2FDwFcONh1s6XmTJx%2F3u6npUfOS16qhTy2M%2BVMkTe7ur%2BqcuF8ZDf2NoGH7zZLoTe5sdn2xquHW9X2JBc%2BxtuSrQQBbPef%2FR1Kgt%2Fb5WdDcrQ%3D%3D" width="342" heigth="166"></p>

Gracias a lo aprendido en clase, se vuelven las imagenes a escala de grises para disminuir la cantidad de informacion sin perder la informacion vital, dejando las imagenes de esta forma:
<p align="center"><img src="https://storage.googleapis.com/kaggle-datasets/3258/5337/amer_sign3.png?GoogleAccessId=web-data@kaggle-161607.iam.gserviceaccount.com&Expires=1550816903&Signature=TYJYPvnB54jCIGjvOyh5QR5tS73nZ6mG%2F3wlpIkiP%2FDM3hq%2BfIcJTFZrnc6i5MjIu7RM%2ByLD1aftsbn1Jw7Xj%2FdiKGMet6DK7A76v5KaXFxLc3huawlV5Lf4AIAnAR9k5zXxFvUet%2BZDIvs5ObbfbZT3rkHWP1%2Fj3Efc5mHK5yVGLh4soF4gbL%2BsslEB0PXM5c11fxmPfQ8%2FY96JW60sfitDZ2gAhG7IDI04E3MhpVKvtvkxVePw85%2Fx4R33bh3Chvwp5iM6B5tguTDMzfFt5wy8c5KIvZn00fq3XT6JBVTvyWv%2FyQvzAMojRU37y5co4Fu%2BqQNBJ%2FsJ9acBuZushA%3D%3D" width="342" heigth="166"></p>

Utilizando los algoritmos vistos en clase, se procede a entrenar un modelo, con el cuál se realizará clasificación.



# Objetivo
Reconocer señas a partir de imágenes y clasificarlas en sus correspondientes letras del abecedario para traducir del lenguaje de señas a inglés. 

# Referencias
Los datos del dataset fueron recolectados por usuarios de que manejan el lenguaje de señas a la perfeccion, y fueron extraidos de:
- https://www.kaggle.com/datamunge/sign-language-mnist#amer_sign2.png
- https://www.kaggle.com/datamunge/sign-language-mnist#amer_sign3.png
- https://www.kaggle.com/datamunge/sign-language-mnist#american_sign_language.PNG
- https://www.kaggle.com/datamunge/sign-language-mnist#sign_mnist_test.zip
- https://www.kaggle.com/datamunge/sign-language-mnist#sign_mnist_train.zip
