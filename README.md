# Organelo Ninja

Estilo Fruit Ninja, pero con organelos celulares y controlado con la mano frente a la cámara (detección con MediaPipe Hand Landmarker, todo en el navegador).

- Corta organelos moviendo rápido el dedo índice.
- No cortes el núcleo.
- Cada corte muestra la función del organelo.
- Sin cámara también se juega con el mouse o en pantalla táctil.

## Jugar localmente

La cámara necesita `localhost` o HTTPS:

```bash
python -m http.server 8093
```

Luego abre http://localhost:8093 y permite el acceso a la cámara.
