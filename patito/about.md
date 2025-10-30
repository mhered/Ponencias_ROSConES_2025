Original application to the CFP:

# ROS, LeRobot y un patito de goma: robótica e inteligencia artificial accesible

----

¿De verdad necesitamos URDFs kilométricos, solvers de cinemática inversa, hardware caro y entornos de simulación para controlar un manipulador robótico? En esta charla lo probamos: un brazo open-source de 100 € y un patito de goma nos sirven para demostrar en vivo el control básico a nivel de servo, aplicaciones avanzadas con ROS2 y finalmente modelos de IA de LeRobot que aprenden por demostración y funcionan sorprendentemente bien en el mundo real. Ningún animal de goma sufrirá daños en la demostración, pero alguna de las ideas tradicionales sobre robótica puede que sí.

----

Porque conecta ROS2 y LeRobot con un proyecto abierto, documentado y replicable que facilita a la comunidad el acceso a aplicaciones de inteligencia artificial para manipulación robótica. Además, la demo en vivo es la caña y si no aceptáis la charla el patito se pondrá muy triste.

----

Esta charla propone un recorrido práctico desde la robótica clásica con ROS2 hasta las nuevas técnicas de aprendizaje por imitación con LeRobot (Hugging Face), aplicado a un brazo robótico de bajo coste (SOARM100).

Combina varios factores que la hacen relevante para ROSCon España:

- **Integración real con el ecosistema ROS2**: MoveIt para cinemática, Gazebo Harmonic para simulación, RVIZ para visualización, OpenCV para percepción.
- **Extensión de LeRobot hacia ROS**: uso de modelos preentrenados y entrenamiento por teleoperación para manipulación robusta sin necesidad de modelados complejos.
- **Código abierto y accesible**: todo el material está disponible en GitHub (mhered/my_SOARM100), incluyendo URDF, ejemplos y documentación.
- **Demo en vivo**: manipulación de un patito de goma como objeto de prueba, que introduce un guiño humorístico pero a la vez conecta con la tradición educativa (duck debugging, Duckietown).

La propuesta es novedosa porque pone frente a frente dos enfoques:

1. **Robótica “clásica**, que requiere modelado explícito del robot, cinemática, control de trayectorias, percepción, simulación, etc
2. **Robótica “con IA**”, en la que el robot se trata como una caja negra y se entrena por imitación, consiguiendo resultados sorprendentemente robustos frente a condiciones cambiantes.

Este contraste permite reflexionar sobre las oportunidades y retos que la IA abre dentro del ecosistema ROS.

El proyecto tiene también un componente **educativo y comunitario**: el hardware SOARM100 de TheRobotStudio es reproducible con impresión 3D y componentes económicos (menos de 100 €), lo que lo convierte en una plataforma excelente para contextos educativos. Un worshop basado en este trabajo fue el proyecto más votado durante **PyCamp España 2025** , y en **PyConES 2025** se aceptó una charla derivada, orientada a principiantes. La propuesta de charla para ROSCon se centra en la **integración técnica entre ROS y la plataforma LeRobot**, dirigida a un público profesional y académico.

En resumen, esta charla aporta:

- **Relevancia**: uso extensivo de ROS2 y su ecosistema.
- **Novedad**: integración con LeRobot y aprendizaje por imitación.
- **Impacto**: proyecto accesible, abierto y replicable.
- **Claridad y diversión**: demo en vivo con un guiño al patito de goma.

Necesidades técnicas mínimas: una mesa y toma de corriente. Idealmente una cámara para mostrar en pantalla el brazo robótico en acción si la sala es grande, aunque no es imprescindible.

---

