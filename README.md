# 🏎️ CUBE RACING
**Developed by CUBE DEV**

Un motor de carreras arcade ligero desarrollado en **Three.js** con un enfoque en la fidelidad técnica, multijugador *peer-to-peer* y soporte nativo para periféricos. **CUBE RACING** combina una estética retro-futurista con mecánicas modernas de simulación de físicas.

---

## 🚀 Características Principales

* **Motor Gráfico 3D:** Renderizado de alto rendimiento utilizando WebGL a través de la librería `Three.js`.
* **Sistema Multijugador Real:** Integración con **PeerJS (WebRTC)** para permitir duelos 1v1 sin necesidad de un servidor centralizado.
* **Soporte Avanzado para Gamepad:** Mapeo de precisión para gatillos analógicos (RT/LT) y joysticks, incluyendo feedback táctil (vibración).
* **Social Hub:** Sistema dinámico de gestión de amigos, búsqueda por ID único y gestión de solicitudes en tiempo real.
* **Estética Cyberpunk:** HUD digital minimalista, efectos de iluminación emisiva y personalización de neones para los vehículos.

## 🛠️ Stack Tecnológico

* **Lenguaje:** JavaScript (ES6+).
* **Gráficos:** [Three.js](https://threejs.org/) (WebGL).
* **Networking:** [PeerJS](https://peerjs.com/) (WebRTC).
* **UI/UX:** HTML5 / CSS3 (Google Fonts: Orbitron & Rajdhani).

## 🎮 Controles

### ⌨️ Teclado
| Acción | Tecla |
| :--- | :--- |
| Acelerar | `W` |
| Frenar / Reversa | `S` |
| Girar | `A` / `D` |
| Pausa | `ESC` |

### 🎮 Mando (Recomendado)
| Acción | Botón / Eje |
| :--- | :--- |
| Acelerar | `Gatillo Derecho (RT/R2)` |
| Frenar / Reversa | `Gatillo Izquierdo (LT/L2)` |
| Dirección | `Joystick Izquierdo` |
| Nitro | `Botón A / Cross` |

## 📦 Instalación y Uso

1.  **Clona este repositorio:**
    ```bash
    git clone [https://github.com/TU_USUARIO/cube-racing.git](https://github.com/TU_USUARIO/cube-racing.git)
    ```
2.  **Ejecución:**
    Abre el archivo `index.html` en cualquier navegador moderno. 
    *Nota: Para que el multijugador funcione correctamente, se recomienda usar un servidor local (Live Server en VS Code) debido a las políticas de seguridad de WebRTC.*

3.  **Conexión:**
    Comparte tu **CUBE-ID** generado automáticamente en el Social Hub para iniciar un duelo.

---
**CUBE RACING** es un proyecto en constante evolución. ¡Feedback y contribuciones son bienvenidos!
