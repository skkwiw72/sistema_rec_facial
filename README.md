# sistema_rec_facial
explicacion :
Este proyecto se centra en el desarrollo de un sistema de inicio de sesión que combina métodos tradicionales con reconocimiento facial para mejorar la seguridad y experiencia del usuario. Aquí están las principales características y funciones:
    Registro Convencional:
        Permite a los usuarios crear una cuenta proporcionando un nombre de usuario y una contraseña.
        Los datos se almacenan de forma segura en archivos individuales.

    Registro Facial:
        Captura el rostro del usuario a través de la cámara para el registro.
        La imagen facial se guarda y procesa para su posterior comparación.

    Inicio de Sesión Tradicional:
        Los usuarios pueden iniciar sesión con su nombre de usuario y contraseña previamente registrados.
        Se verifica la autenticación a través de la comparación con los datos almacenados.

    Inicio de Sesión Facial:
        Captura una imagen facial en el momento del inicio de sesión para su posterior comparación.
        Se utiliza un algoritmo de comparación de características para verificar la autenticidad.

    Comparación de Rostros:
        Utiliza la técnica de ORB (Oriented FAST and Rotated BRIEF) para calcular similitudes entre imágenes faciales.

    Interfaz Gráfica de Usuario (GUI):
        Proporciona una interfaz intuitiva para la interacción del usuario.

    Bibliotecas y Tecnologías Utilizadas:
        Tkinter: Para la creación de la interfaz gráfica.
        OpenCV: Para el procesamiento de imágenes y captura de video.
        MTCNN (Multi-Task Cascaded Convolutional Networks): Para la detección facial.
        Matplotlib: Para visualización de imágenes y gráficos.

Este proyecto se enfoca en brindar una experiencia de inicio de sesión segura y conveniente, utilizando tanto métodos tradicionales como tecnologías de reconocimiento facial. Su objetivo es proporcionar una alternativa innovadora y eficiente para la autenticación de usuarios.
