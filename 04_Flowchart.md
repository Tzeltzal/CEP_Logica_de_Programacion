# Diagrama de Flujo o Flowchart

> Represemtación gráfica de un algoritmo por medio de símbolos relacionados que indican el orden de ejecución

Se caracterizan por

- Tener solo un punto de inicio y fin del programa

- Ejecutarse de arriba hacia abajo y de izquierda a derecha

Los símbolos para un **Diagrama de Flujo** son

```mermaid
flowchart TD
    %% Simbología Estándar de Diagramas de Flujo

    %% 1. Inicio / Fin (Terminal)
    A([Inicio / Fin]) --> B[/Entrada / Salida/]

    %% 2. Entrada / Salida de Datos
    B --> C[Proceso / Acción]

    %% 3. Proceso
    C --> D{Toma de Decisión}

    %% 4. Decisión
    D -- Sí --> E[(Base de Datos)]
    D -- No --> F[/Documento Impreso/]

    %% 5. Almacenamiento / Documentación
    E --> G((Conector))
    F --> G

    %% 6. Subproceso o Proceso Definido
    G --> H[[Subproceso / Función]]
    
    H --> I([Fin])
```
