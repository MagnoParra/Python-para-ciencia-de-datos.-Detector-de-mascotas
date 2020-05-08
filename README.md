# Python-para-ciencia-de-datos.-Detector-de-mascotas
Detector de mascotas usando Mask RCNN y la dataset Coco

Utilizando un modelo preentrenado (mask_rcnn_coco.h5)

Requiere la instalación de tensorflow 1.13 para poder utuilizar la función log

!pip install tensorflow==1.13.0rc0

Reemplazar la ruta de las imagenes en la parte:

image = skimage.io.imread('/content/pasearmascotas.jpg')


Reemplazar la ruta del video en las partes:

capture = cv2.VideoCapture(os.path.join(VIDEO_DIR, 'trailer1.mp4'))

y

video = cv2.VideoCapture(os.path.join(VIDEO_DIR, 'trailer1.mp4'));

Se toman 30 frames por segundo, se procesan 3 frames por minuto aproximadamente.

Se genera el archivo out.mp4



Basado en:
https://github.com/matterport/Mask_RCNN

https://github.com/Tony607/colab-mask-rcnn
