# Master Agentic AI

Material de curso y ejercicios prácticos sobre **IA Agéntica**: desde sistemas basados en reglas hasta agentes construidos sobre LLMs, sus componentes, seguridad y el ecosistema de 2025.

Cada módulo incluye un notebook de **Ejemplo** (`Code Example`) con la implementación guiada y un notebook de **Ejercicio** (`Code Exercise`) para practicar.

## Contenido

| Módulo | Tema | Ejemplo | Ejercicio |
|--------|------|:-------:|:---------:|
| 1.1 | De los sistemas basados en reglas a los agentes LLM | ✅ | ✅ |
| 1.2 | Componentes centrales de un agente — implementación práctica | ✅ | ✅ |
| 1.3 | LLMs como motores de razonamiento — implementación práctica | ✅ | ✅ |
| 1.4 | Seguridad en IA Agéntica — modelado de amenazas y safety | ✅ | ✅ |
| 1.5 | El ecosistema agéntico de 2025 | ✅ | ✅ |

## Requisitos

- Python 3.10+
- Una clave de API de OpenAI

## Configuración

1. Clona el repositorio:

   ```bash
   git clone https://github.com/abantodca/Master_Agentic_AI.git
   cd Master_Agentic_AI
   ```

2. Crea y activa un entorno virtual:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # En Windows: .venv\Scripts\activate
   ```

3. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Crea un archivo `.env` en la raíz con tu clave de API:

   ```env
   OPENAI_API_KEY=tu_clave_aqui
   ```

   > El archivo `.env` está en `.gitignore`, por lo que tu clave nunca se sube al repositorio.

## Uso

Lanza JupyterLab y abre los notebooks:

```bash
jupyter lab
```

Empieza por el módulo 1.1 y avanza en orden. Trabaja primero el notebook de *Ejemplo* y luego completa el de *Ejercicio* correspondiente.

## Estructura del proyecto

```
Master_Agentic_AI/
├── Code+Example+1.1 ... 1.5    # Notebooks guiados
├── Code+Exercise+1.1 ... 1.5   # Notebooks de práctica
├── requirements.txt            # Dependencias
├── .gitignore
└── README.md
```

## Dependencias principales

- `openai` — cliente del API de LLM
- `python-dotenv` — carga de variables de entorno desde `.env`
- `jupyterlab` / `ipykernel` — ejecución y edición de los notebooks
