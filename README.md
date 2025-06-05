# 📦 Proyecto: Pondering Pond
Autor: Carlos Rocamora Colomer (crc89)
Plataforma: Meta Quest 3
Motor: Unreal Engine 5.4.4
Duración de la experiencia: 2–4 minutos

## 🎮 Descripción de la experiencia
Pondering Pond es una experiencia inmersiva de realidad virtual desarrollada para Meta Quest 3, en la que el jugador puede relajarse y concentrarse en sus pensamientos o pescar peces globo que flotan a su alrededor.

## 🕹️ Cómo jugar / Controles
A continuación se detallan los controles básicos para interactuar dentro del juego. Se recomienda jugar sentado o de pie, en una zona despejada.
![Controles](https://github.com/user-attachments/assets/26b72b5f-4199-4293-9565-33d2aa71ac53)


## 📜 Licencias
Los siguientes assets de terceros han sido utilizados bajo sus respectivas licencias:

    Nombre del asset: Emerald Forest - Chill Music for Relaxation Sleep and Meditation
    Ruta en proyecto: /Project/Content/Audio
    Fuente: [Julius H.]() from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=5536)

    Nombre del asset: PICO OpenXR (Plugin usado para testear el juego en unas gafas PICO 4)
    Fuente: https://www.fab.com/es-es/listings/a7eb0f28-d7f1-4b30-8d2d-49d12eeb1d62

    Nombre del asset: VR UE5 Template
    Fuente: Epic Games

    Nombre del asset: Logo PonderingPond
    Fuente: Generado con ChatGPT



# 🎤 Entrevista
## 🛠️ Proceso de creación
Durante el desarrollo de esta experiencia VR me enfoqué en la implementación de una mecánica realista de una caña de pescar basada en físicas, la cual fue desarrollada usando como base del equipable el arma de la plantilla VR de Unreal Engine, pero fue modificada en gran medida y se le añadieron todo los extras como la forma visual, el hilo que une el cuerpo con el corcho, y el propio corcho el cual limita su distancia con la punta de la caña mediante un Physics Constraint y esa fue la parte más complicada de ejecutar, ya que hubo muchis problemas con la jerarquía de componentes, la herencia de movimientos físicos entre los cuerpos y el control desafiante pero simple de la inercia y me aseguré de hacer una prueba técnica en las Meta Quest 3 para asegurar que el rendimiento fuera aceptable.

## 🔮 Siguientes pasos
Con más tiempo me gustaría:

    Añadir un sistema de progresión como una tienda de mejoras para aumentar la rejugabilidad.

    Incorporar más tipos de interacción física como coger los peces de la punta de la caña y dejarlos en un cubo
    
    Añadir entornos variados y más complejos.

    Mejorar la ambientación sonora con efectos de audio.
