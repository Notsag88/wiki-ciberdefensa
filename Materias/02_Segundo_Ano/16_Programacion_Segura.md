# 16 - Programación Segura

## 📋 Información de Cursada
* **Carga Horaria**: 80 horas totales.
* **Distribución**: 40 hs Teóricas / 40 hs Prácticas.
* **Correlativas para cursar**: Lenguajes de Programación (10), Sistemas de Tratamiento de Datos (06) e Infraestructura de Telecomunicaciones (07).
* **Correlativas que abre**: Ciberseguridad Aplicada (17) y Práctica Profesional Supervisada (36).

---

## 🎯 Objetivos de Aprendizaje
* Identificar y mitigar las vulnerabilidades de software más comunes (OWASP Top 10, CWE).
* Aplicar principios de diseño seguro como "Mínimo Privilegio" y "Defensa en Profundidad".
* Dominar técnicas de validación de entradas y manejo seguro de memoria para prevenir exploits.
* Integrar la seguridad en todas las fases del ciclo de vida de desarrollo de software (S-SDLC).

---

## 📚 Contenidos Mínimos y Mapeo de Bibliografía

### Unidad 1: Fundamentos y Ciclo de Vida Seguro (S-SDLC)
* **Temas**: Principios de diseño seguro de Saltzer y Schroeder. Amenazas y modelos de confianza. Integración de seguridad en metodologías Ágiles y DevOps (DevSecOps).
* **Mapeo**:
    * **Howard & LeBlanc**: Cap. 1 al 3 (The Need for Secure Systems).
    * **OWASP**: SAMM (Software Assurance Maturity Model).

### Unidad 2: Seguridad en la Gestión de Memoria
* **Temas**: Corrupción de memoria: Buffer Overflow, Stack smashing, Heap overflow e inyecciones de punteros. Mitigaciones modernas (ASLR, DEP, Canary).
* **Mapeo**:
    * **Seacord (CERT)**: Cap. 2 (Strings) y Cap. 5 (Dynamic Memory Management).
    * **Erickson**: Cap. 0x300 (Exploitation).

### Unidad 3: Vulnerabilidades de Inyección y Lógica
* **Temas**: Inyección de código (SQLi, Command Injection, XSS). Fallos en la gestión de sesiones y autenticación. Cross-Site Request Forgery (CSRF).
* **Mapeo**:
    * **Zalewski**: Cap. 10 al 12 (Browser Security Model).
    * **OWASP**: Guide to SQL Injection.

### Unidad 4: Criptografía Aplicada al Desarrollo
* **Temas**: Almacenamiento seguro de credenciales (hashing y salting). Protección de datos en tránsito y en reposo. Errores comunes en la implementación de librerías criptográficas.
* **Mapeo**:
    * **Howard & LeBlanc**: Cap. 8 (Cryptographic Foibles).
    * **Seacord**: Cap. 9 (Criptografía).

### Unidad 5: Análisis de Código y Testing de Seguridad
* **Temas**: Análisis estático (SAST) y dinámico (DAST). Pruebas de penetración de aplicaciones (SAST). Auditoría de librerías de terceros (SCA).
* **Mapeo**:
    * **OWASP**: Testing Guide (WSTG).
    * **McGraw**: Cap. 5 (Software Pen Testing).

---

## 📝 Bitácora de Seguimiento
- [ ] **Unidad 1**: [ ] Principios de Saltzer estudiados | [ ] Modelado de amenazas (STRIDE).
- [ ] **Unidad 2**: [ ] Demo de Buffer Overflow controlada | [ ] Uso de Valgrind/GDB.
- [ ] **Unidad 3**: [ ] Mitigación de SQLi con Prepared Statements | [ ] Laboratorio XSS.
- [ ] **Unidad 4**: [ ] Implementación de Argon2/BCrypt | [ ] Uso correcto de TLS/SSL.
- [ ] **Unidad 5**: [ ] Reporte de análisis estático (SonarQube/Snyk) | [ ] Fuzzing básico.
- [ ] **Parcial 1**: [ ] Fecha confirmada | [ ] Nota: ___.
- [ ] **Parcial 2**: [ ] Fecha confirmada | [ ] Nota: ___.

---

## 📖 Bibliografía de Elite Recomendada
1. **Michael Howard & David LeBlanc - "Writing Secure Code"**: El libro de referencia de Microsoft que sentó las bases de la programación defensiva moderna.
2. **Robert Seacord - "Secure Coding in C and C++" (SEI CERT)**: La guía técnica definitiva para evitar vulnerabilidades de bajo nivel.
3. **Michał Zalewski - "The Tangled Web"**: Imprescindible para entender la seguridad en aplicaciones web y navegadores.
4. **Gary McGraw - "Software Security: Building Security In"**: Un enfoque integral sobre cómo gestionar la seguridad en proyectos de software a gran escala.

---

## ⚖️ Condición de Aprobación
* **Promoción Directa**: Mínimo **7** en cada parcial y entrega de proyecto de software auditado.
* **Examen Final**: Mínimo **4** en parciales para habilitar el examen final.