Mercury
=======

Inspirados en el éxito obtenido por google en el desarrollo de vehículos autónomos y mediante el conocimiento adquirido en el curso de programación llevado en Udacity (Programming a Robotic Car) dictado por el profesor Sebastian Thrun. Hemos decidio aventurarnos a desarrollar el primer vehículo autónomo de la Universidad Católica de Santa María, Arequipa, Perú.

Para esto utilizaremos el Go-Kart del programa profesional de Ingeniería Mecánica, Mecánica Eléctrica y Mecatrónica, el cual modificaremos y programaremos hasta conseguir el mejor agente de conducción autónoma inteligente que podamos.

Los tópicos investigados serán:

* **Localización**: Aplicaremos métodos probabilísticos de localización como "Monte Carlo Localization" y "Particles Filters", para aumentar la presición de posicionamiento entregada por el GPS abordo.

* **Medición**: Este campo ocupara filtros de Kalman para sensar objetos dínamicos y estáticos, los cuales agregaran información del entorno a nuestro agente de conducción.

* **Planeamiento**: Utilizaremos el agoritmo de búsqueda A* junto con programación dinámica para obtener la mejor ruta hacia un destino fijado por orden ingresada u orden pre-programada.

* **Control de la dirección**: Aplicaremos un suavizado de rutas al resutado obtenido en el planeamiento, para que pueda ser utilizado como referencia en la dirección del vehículo. La dirección utilizara un controlador PID sintonizado mediante el algoritmo Twiddle.

* **SLAM**: Este es un tópico extra en el que utilizaremos graph SLAM (dependiendo de la evolución del proyecto, se decidira sobre la inclusión definitiva de esta técnica).
