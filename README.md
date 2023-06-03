1. Desde un notebook o una terminal debes instalar la libreria ejecutando el siguiete comando: pip install FAC/FAC-0.0.1-py3-none-any.whl  
2. Abre un notebook e importas la libreria: import FAC as FAC  
3. La libreria contiene dos funciones: a)procesar el video y b) Hallar etiquetas.  
4. La función video_a_imagenes espera la ruta donde previamente se guardar el video. Ej: (video/video.mpg)  
Ej:  
import FAC as FAC  
FAC.video_a_imagenes(input_path)  
FAC.etiquetar()  
