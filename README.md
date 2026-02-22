# Proyecto Python con Tests

Proyecto de Práctica para probar que el entorno de programación está configurado y listo para realizar los talleres.

## Estructura del Proyecto

```
practica/
├── main.py            # código principal con funciones
├── tests/
│   ├── conftest.py    # configuración de pytest
│   └── test_main.py   # tests para las funciones
└── README.md
```

## Funcionalidades

El proyecto incluye dos funciones simples pero bien documentadas:

1. **`suma(a, b)`**: Calcula la suma de dos números
2. **`es_par(n)`**: Determina si un número es par

## Configuración de Desarrollo

### Prerrequisitos

- Python 3.13 o superior
- pip (gestor de paquetes de Python)

### Instalación

1. Clona el repositorio:

```bash
git clone https://github.com/UR-CC/practica.git
cd practica
```

2. Instala las dependencias:

```bash
pip install pytest ruff
```

### Ejecutar el Programa

```bash
python main.py
```

### Ejecutar Tests

```bash
# Ejecutar todos los tests
pytest

# Ejecutar tests con detalles
pytest -v
```

