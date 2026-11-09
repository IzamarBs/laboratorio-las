# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Helen Izamar Gonzalez Bolaños
- **Carné:** (no me han dado id)
- **Correo institucional:**  helengonzalez298@gmail.com
- **Asignatura:** LENGUAJES DE PROGRAMACIÓN CON ASPECTOS DE SEGURIDAD
- **Fecha:** 08/10/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
repositorio/
├── proyecto/
│   ├── app.py
│   ├── requirements.txt
│   └── otros archivos
└── README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone URL_DEL_REPOSITORIO
```

**Paso 2.** Ingresar al proyecto.

```bash
cd repositorio/proyecto
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```
## 5. Tabla de Resultados  
Prueba               MTTD            MTTR
1                    50.0 s          434.0 s
2                    35.0 s          104.0 s
3                    32.0 s          55.0  s
PROMEDIO             39              197.6666

```