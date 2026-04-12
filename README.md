# 🦠 Virus & Security Projects

Esta carpeta contiene proyectos del currículo de Seguridad y Malware de 42 School, enfocados en auto-replicación, recursión, inyección de memoria y la comprensión profunda de cómo operan los programas maliciosos.

## Proyectos

### [🔄 Dr. Quine](./dr-quine/) - Recursión y Auto-replicación
Exploración profunda del teorema de recursión de Kleene a través de la creación de programas auto-replicantes (*Quines*). El objetivo principal es escribir código que, sin recurrir a leer archivos externos, imprima exactamente su propio código fuente original al ejecutarse.
**Estado:** ✅ Completado

**Características destacadas:**
- 🧬 **Colleen:** Creación de un quine básico incorporando comentarios y control de flujo en funciones separadas.
- 🌀 **Grace:** Implementación de auto-replicación basada estrictamente en el uso de macros preprocesadas que depositan su código en archivos hijos.
- 🦠 **Sully:** Expansión recursiva de un programa que se auto-compila y ejecuta en cascada generando múltiples copias cronometradas.
- 📜 **Restricción absoluta:** Ausencia total de operaciones IO de lectura de disco (como `open`, `read`), confiando puramente en matemáticas e interpolación de cadenas.

**Stack:** C, Assembly x86-64 (NASM), Shell Scripting

### [🌲 Woody Woodpacker](./woody-woodpacker/) - Inyección ELF y Criptografía
Desarrollo de un packer/crypter polimórfico. El programa inyecta un payload en ensamblador dentro de las Code Caves de archivos ELF de 64 bits ajenos y los cifra utilizando matemáticas simétricas RC4.
**Estado:** ✅ Completado

**Características destacadas:**
- 💉 Inyección de **Payloads ASM** en memoria.
- 🔐 Implementación desde cero del algoritmo **Rivest Cipher 4 (RC4)**.
- 🦠 Ejecución invisible (*Stealth*) y resolución dinámica del Original Entry Point (OEP).
- 🧠 Documentación exhaustiva en español de la deconstrucción de cabeceras **ELF64**.

**Stack:** C, Assembly x86-64 (NASM), Bash avanzado (Testing)

---

## Objetivos de Aprendizaje

Los proyectos en esta carpeta están diseñados para:

1. **Comprender la auto-replicación e infección** → Cómo los programas pueden reproducirse a sí mismos y camuflarse dentro de otros procesos.
2. **Teoría de la computación** → Teorema de recursión, puntos fijos y criptografía algorítmica.
3. **Seguridad informática** → Fundamentos de cómo funcionan virus polimórficos, crypters y malware.
4. **Programación de bajo nivel** → Control milimétrico sobre la memoria RAM (System Calls, mmap, Assembly).

Estos proyectos sirven como introducción fundamental a temas más avanzados de seguridad y análisis defensivo de malware.

---

<div align="center">

[⬅️ Volver al repositorio principal](../README.md)

</div>
