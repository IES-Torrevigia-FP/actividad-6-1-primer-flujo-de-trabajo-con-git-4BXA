# Reflexión 6-1

# Diferencias entre directorio de trabajo, zona de staging e historial de commits

- **Directorio de trabajo:** Es donde editas tus archivos. Aquí ves y modificas tu proyecto en tiempo real.  
- **Zona de staging (área de preparación):** Es como un “borrador” donde eliges qué cambios quieres incluir en el próximo commit.  
- **Historial de commits:** Es el registro permanente de los cambios que has confirmado, mostrando la evolución del proyecto.

# Error típico en el flujo de Git y cómo evitarlo

Un error común es **olvidarse de usar git add** antes de hacer un commit. Esto provoca que los cambios no se guarden en el historial. Para evitarlo, revisar siempre el estado con git status y asegurarse de que los archivos modificados estén staged antes de commitear.

# Ventaja de decidir qué cambios entran en cada commit

Permite crear commits claros y específicos, facilitando la revisión y la comprensión del historial del proyecto.
Esto ayuda a aislar errores y documentar el proceso de desarrollo de manera más ordenada.
