# FaceRecognition-project

Ce script Python détecte les visages dans un flux vidéo de caméra en utilisant la bibliothèque face_recognition. Il affiche le flux vidéo avec des rectangles autour des visages trouvés en utilisant la bibliothèque OpenCV. Le script compare les visages encodés avec les visages dans le dossier de dataset 'faces' en utilisant face_recognition.compare_faces(). Si une correspondance est trouvée, il affiche le nom et le niveau de précision. La fonction precision() est utilisée pour calculer le niveau de précision de notre detection. 

Le script se termine lorsque l'utilisateur appuie sur la touche 'q'.