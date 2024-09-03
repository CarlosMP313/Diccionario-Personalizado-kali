# Diccionarios Personalizados con CUpp

CUpp (Common User Passwords Profiler) es una herramienta útil para crear diccionarios de contraseñas personalizados basados en la información del usuario objetivo. A continuación, se detalla cómo instalar y usar CUpp para generar estos diccionarios.

## 1. Instalación de CUpp

### 1.1. Descargar CUpp
1. Visita el repositorio de CUpp en GitHub: [CUpp en GitHub](https://github.com/Mebus/cupp.git).
2. Copia la URL HTTPS para clonar el repositorio.

### 1.2. Clonar el Repositorio
1. Abre la terminal y navega a la carpeta donde deseas clonar CUpp.
2. Ejecuta el siguiente comando en la terminal:
   ```bash
   git clone <URL_copiada>
## CUpp ya estará instalado en tu sistema.

### 2. Iniciar CUpp
Para iniciar CUpp, utiliza el siguiente comando:

```bash
python3 cupp.py -h
```
> **Nota:** Si no tienes Python instalado, descárgalo e instálalo desde [python.org](https://www.python.org).

## 2.1. Opciones Principales
Cuando ejecutes CUpp, verás varias opciones:

- `-h` : Muestra el menú de ayuda.
- `-i` : Realiza preguntas interactivas para crear un perfil de contraseñas personalizado.
- `-w` : Usa un diccionario existente para perfilar o usar la salida de WyD.pl para generar más contraseñas.
- `-l` : Descarga listas de palabras grandes desde el repositorio.
- `-a` : Analiza nombres de usuarios y contraseñas predeterminadas directamente desde la base de datos de Alecto.
- `-v` : Muestra la versión del programa.

## 2.2. Crear un Diccionario Personalizado
La opción que nos interesa es `-i` para crear un diccionario personalizado. Ejecuta:

```bash
python3 cupp.py -i
Responde todas las preguntas con la mayor cantidad de información posible sobre la víctima.

## 2.3. Configuraciones Adicionales
- CUpp te preguntará si deseas agregar más palabras clave de la víctima. Responde "sí" (`y`) si tienes más palabras, de lo contrario, responde "no" (`n`).
- CUpp también te preguntará si deseas incluir caracteres especiales. Es recomendable responder "sí" (`y`).
- Cuando te pregunte si deseas agregar números aleatorios, también responde "sí" (`y`).
  
  > **Nota:** Esto genera más combinaciones de claves.

- Cuando te pregunte si deseas activar el modo "leet" (sustituciones de letras por números y símbolos), responde "sí" (`y`).

## 2.4. Confirmación de Combinaciones
- CUpp te mostrará las combinaciones generadas y te preguntará si deseas continuar. Responde "sí" (`y`).
- El proceso puede tomar tiempo dependiendo de la cantidad de información proporcionada.

## 3. Finalización
- Una vez que el proceso termine, tu diccionario personalizado estará listo para usarse.

¡Listo! Ahora tienes un diccionario de contraseñas personalizado creado con CUpp.
```

> **Descargo de responsabilidad:** No soy responsable por el uso indebido de la información proporcionada en este proceso. El uso de CUpp debe realizarse con fines éticos y legales, respetando la privacidad y los derechos de los demás. Asegúrate de tener el consentimiento adecuado antes de recopilar y utilizar cualquier información personal.
