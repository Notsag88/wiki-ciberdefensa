# 09 - Sistemas Operativos II

## 📋 Información de Cursada
* **Carga Horaria**: 64 horas totales.
* **Distribución**: 32 hs Teóricas / 32 hs Prácticas.
* **Correlativas para cursar**: Sistemas Operativos I (05).
* **Correlativas que abre**: Informática Forense (25).

---

## 🎯 Objetivos de Aprendizaje
* Comprender la gestión de procesos y el uso de hilos (threads) en sistemas modernos.
* Dominar los algoritmos de planificación de CPU y la comunicación entre procesos (IPC).
* Resolver problemas de concurrencia, sincronización y bloqueos mutuos (deadlocks).
* Analizar los mecanismos de protección y seguridad de los sistemas operativos.

---

## 📚 Contenidos Mínimos y Mapeo de Bibliografía

### Unidad 1: Procesos e Hilos (Threads)
* **Temas**: Concepto de proceso, estados y bloqueos de control (PCB). Concepto de hilo, multihilos y modelos de hilos.
* **Mapeo**:
    * **Silberschatz**: Cap. 3 (Process Concept) y Cap. 4 (Multithreaded Programming).
    * **Tanenbaum**: Cap. 2.1 (Processes) y Cap. 2.2 (Threads).

### Unidad 2: Planificación de la CPU
* **Temas**: Criterios de planificación, algoritmos (FCFS, SJF, Priority, Round Robin, Multilevel Queues). Planificación en tiempo real.
* **Mapeo**:
    * **Silberschatz**: Cap. 5 (CPU Scheduling).
    * **Tanenbaum**: Cap. 2.4 (Scheduling).

### Unidad 3: Concurrencia y Sconización
* **Temas**: El problema de la sección crítica, semáforos, monitores y pasaje de mensajes. Problemas clásicos (Cena de los filósofos, Productores-Consumidores).
* **Mapeo**:
    * **Silberschatz**: Cap. 6 (Synchronization Tools) y Cap. 7 (Synchronization Examples).
    * **Tanenbaum**: Cap. 2.3 (Interprocess Communication).

### Unidad 4: Bloqueos Mutuos (Deadlocks)
* **Temas**: Caracterización, métodos de prevención, evitación y detección. Algoritmo del Banquero.
* **Mapeo**:
    * **Silberschatz**: Cap. 8 (Deadlocks).
    * **Tanenbaum**: Cap. 6 (Deadlocks).

### Unidad 5: Sistemas de Archivos y Seguridad
* **Temas**: Interfaz y estructura del sistema de archivos. Métodos de asignación y gestión de espacio libre. Protección y seguridad: dominios de protección, matrices de acceso y amenazas.
* **Mapeo**:
    * **Silberschatz**: Cap. 11, 12 (File-System) y Cap. 14, 15 (Protection & Security).
    * **Tanenbaum**: Cap. 4 (File Systems) y Cap. 9 (Security).

---

## 📝 Bitácora de Seguimiento
- [ ] **Unidad 1**: [ ] Diferencia Proceso vs Hilo | [ ] Ciclo de vida del proceso.
- [ ] **Unidad 2**: [ ] Cálculo de tiempos de espera (Gantt) | [ ] Algoritmo Round Robin.
- [ ] **Unidad 3**: [ ] Implementación de Semáforos | [ ] Resolución de la Sección Crítica.
- [ ] **Unidad 4**: [ ] Condiciones de Coffman | [ ] Ejecución Algoritmo del Banquero.
- [ ] **Unidad 5**: [ ] Estructura de i-nodos | [ ] Permisos y ACLs.
- [ ] **Parcial 1**: [ ] Fecha confirmada | [ ] Nota: ___.
- [ ] **Parcial 2**: [ ] Fecha confirmada | [ ] Nota: ___.

---

## 📖 Bibliografía de Elite Recomendada
1. **Silberschatz, Galvin & Gagne - "Operating System Concepts"**: El manual de referencia para entender la lógica de sincronización y deadlocks.
2. **Andrew S. Tanenbaum - "Modern Operating Systems"**: Fundamental para la parte de IPC (comunicación entre procesos) y seguridad.
3. **William Stallings - "Operating Systems: Internals and Design Principles"**: Excelente para profundizar en el manejo de hilos y multiprocesamiento.
4. **Thomas Anderson & Michael Dahlin - "Operating Systems: Principles and Practice"**: Un enfoque moderno muy orientado a la seguridad y robustez del sistema.

---

## ⚖️ Condición de Aprobación
* **Promoción Directa**: Mínimo **7** en cada parcial (sin recuperatorio).
* **Examen Final**: Mínimo **4** en parciales para habilitar el examen final.