# 🐍 Python — Complete A to Z Frameworks, Libraries & Tools

> Every major Python library/framework organized by domain. This is your master reference.

---

## 🌐 1. WEB FRAMEWORKS

### Full-Stack / Backend Frameworks
| Library | Description |
|---|---|
| **Django** | Full-stack web framework — batteries included (ORM, Admin, Auth, Templates) |
| **Flask** | Lightweight micro-framework — minimal, flexible |
| **FastAPI** | Modern async API framework — fastest Python web framework, auto Swagger docs |
| **Pyramid** | Flexible, starts small, scales to full-stack |
| **Tornado** | Async networking framework — WebSockets, real-time |
| **Bottle** | Single-file micro-framework — lightweight |
| **Falcon** | Ultra-fast, minimalist REST API framework |
| **Sanic** | Async web framework — similar to Flask but async |
| **Starlette** | Lightweight ASGI framework — base for FastAPI |
| **Litestar** | Opinionated, high-performance ASGI framework |
| **Quart** | Async version of Flask |
| **aiohttp** | Async HTTP server + client library |
| **Masonite** | MVC framework inspired by Laravel/Django |
| **Web2py** | Full-stack with built-in IDE, no installation needed |
| **CherryPy** | Object-oriented web framework |
| **Hug** | Simple, fast API framework built on Falcon |
| **BlackSheep** | Fast ASGI web framework |

### Django Extensions & Tools
| Library | Description |
|---|---|
| **django-rest-framework (DRF)** | Build REST APIs with Django |
| **django-ninja** | FastAPI-style API for Django |
| **django-channels** | WebSocket + async support for Django |
| **django-allauth** | Authentication — Google, GitHub, Facebook login |
| **django-cors-headers** | CORS handling for Django |
| **django-filter** | Filtering querysets for DRF |
| **django-storages** | File storage backends (S3, GCS, Azure) |
| **django-celery-beat** | Periodic tasks with Celery in Django |
| **django-debug-toolbar** | Debug panel for Django dev |
| **django-environ** | Env variable management |
| **django-guardian** | Object-level permissions |
| **django-silk** | Profiling for Django |
| **dj-database-url** | Parse database URLs for Django |
| **whitenoise** | Serve static files in production |
| **django-redis** | Redis cache backend for Django |

---

## 📊 2. DATA SCIENCE & ANALYSIS

### Core Data Libraries
| Library | Description |
|---|---|
| **NumPy** | N-dimensional arrays, mathematical operations |
| **Pandas** | DataFrames — data manipulation and analysis |
| **Polars** | Ultra-fast DataFrame library (Rust-backed) |
| **Dask** | Parallel computing — large datasets beyond RAM |
| **Vaex** | Out-of-core DataFrames — billions of rows |
| **Modin** | Drop-in Pandas replacement with parallel processing |
| **PyArrow** | Apache Arrow — columnar in-memory data |
| **cuDF** | GPU-accelerated DataFrames (NVIDIA RAPIDS) |
| **xarray** | N-D labeled arrays — great for scientific data |
| **statsmodels** | Statistical models, tests, and data exploration |
| **SciPy** | Scientific computing — optimization, integration, linear algebra |
| **SymPy** | Symbolic mathematics — algebra, calculus |
| **Awkward Array** | Ragged/nested arrays for particle physics |

### Data Validation & Cleaning
| Library | Description |
|---|---|
| **Pydantic** | Data validation using Python type hints |
| **Cerberus** | Lightweight data validation |
| **Great Expectations** | Data quality testing and documentation |
| **Pandera** | Statistical data validation for Pandas |
| **dataprep** | Fast data cleaning and EDA |

---

## 📈 3. DATA VISUALIZATION

| Library | Description |
|---|---|
| **Matplotlib** | Foundation of Python plotting — highly customizable |
| **Seaborn** | Statistical data viz built on Matplotlib |
| **Plotly** | Interactive charts — line, bar, scatter, 3D |
| **Plotly Express** | Simplified Plotly API |
| **Dash** | Web dashboards with Plotly — no JS needed |
| **Bokeh** | Interactive web-ready visualizations |
| **Altair** | Declarative visualization based on Vega-Lite |
| **Vega-Altair** | Updated Altair with more features |
| **Pygal** | SVG charts |
| **HoloViews** | High-level data visualization |
| **hvPlot** | High-level plotting for Pandas/Dask |
| **Panel** | Dashboard and web app framework |
| **Streamlit** | Build data apps and dashboards instantly |
| **Gradio** | ML model demos with web UI |
| **Folium** | Interactive maps — Leaflet.js in Python |
| **Geopandas** | Geospatial data with Pandas |
| **Cartopy** | Geospatial data visualization |
| **Wordcloud** | Generate word clouds |
| **Missingno** | Visualize missing data |
| **mpl-interactions** | Interactive Matplotlib widgets |
| **vispy** | High-performance interactive 2D/3D visualization |
| **Pyecharts** | Python port of Apache ECharts |

---

## 🤖 4. MACHINE LEARNING

### Core ML Frameworks
| Library | Description |
|---|---|
| **Scikit-learn** | THE machine learning library — classification, regression, clustering |
| **XGBoost** | Gradient boosting — best for tabular data competitions |
| **LightGBM** | Fast gradient boosting by Microsoft |
| **CatBoost** | Gradient boosting by Yandex — handles categorical features |
| **Statsmodels** | Statistical models — OLS, ARIMA, Logit |
| **MLXTEND** | Extensions for scikit-learn — association rules, stacking |
| **TPOT** | AutoML — genetic algorithms for pipeline optimization |
| **H2O.ai** | AutoML platform |
| **Auto-sklearn** | AutoML with scikit-learn |
| **PyCaret** | Low-code ML library |
| **LazyPredict** | Quick model comparison |
| **Imbalanced-learn** | Handling imbalanced datasets — SMOTE, etc. |
| **SHAP** | Model explainability — Shapley values |
| **LIME** | Local interpretable model explanations |
| **ELI5** | Debug and explain ML models |

---

## 🧠 5. DEEP LEARNING

| Library | Description |
|---|---|
| **TensorFlow** | Google's deep learning framework |
| **Keras** | High-level API for TensorFlow |
| **PyTorch** | Most popular research DL framework (Meta) |
| **PyTorch Lightning** | Clean PyTorch boilerplate reduction |
| **JAX** | High-performance ML by Google — NumPy + autograd + GPU |
| **Flax** | Neural networks for JAX |
| **Haiku** | DeepMind's neural network library for JAX |
| **MXNet** | Apache's scalable DL framework |
| **Theano** | (Legacy) Tensor computation with GPU |
| **Caffe** | (Legacy) Deep learning for vision |
| **Paddle** | Baidu's DL framework |
| **MindSpore** | Huawei's AI framework |
| **Trax** | Google Brain's DL library |
| **fastai** | High-level DL library built on PyTorch |
| **ONNX** | Interoperability between DL frameworks |
| **OpenVINO** | Intel's inference optimization toolkit |
| **TensorRT** | NVIDIA GPU inference optimization |
| **TFLite** | TensorFlow for mobile and edge devices |

---

## 💬 6. NATURAL LANGUAGE PROCESSING (NLP)

| Library | Description |
|---|---|
| **NLTK** | Classic NLP toolkit — tokenization, stemming, POS |
| **spaCy** | Industrial-strength NLP — fast and accurate |
| **TextBlob** | Simple NLP — sentiment, translation |
| **Gensim** | Topic modeling — Word2Vec, Doc2Vec, LDA |
| **Transformers (HuggingFace)** | THE NLP library — BERT, GPT, T5, LLaMA |
| **Datasets (HuggingFace)** | Easy access to thousands of NLP datasets |
| **Tokenizers (HuggingFace)** | Fast tokenization |
| **Sentence-Transformers** | Semantic similarity, embeddings |
| **LangChain** | LLM application framework — chains, agents, RAG |
| **LlamaIndex** | Data framework for LLM apps — RAG focused |
| **OpenAI** | Python SDK for GPT-4, Whisper, DALL-E |
| **Anthropic** | SDK for Claude models |
| **Cohere** | NLP API SDK |
| **Haystack** | NLP pipeline framework for search |
| **Flair** | State-of-the-art NLP — NER, classification |
| **fastText** | Facebook's text classification and embeddings |
| **PyMuPDF** | Extract text from PDFs |
| **pdfminer** | PDF text extraction |
| **pytesseract** | OCR — extract text from images |
| **EasyOCR** | Easy optical character recognition |
| **Whoosh** | Full-text search library |
| **Regex (re)** | Built-in regex for pattern matching |
| **langdetect** | Language detection |
| **deep-translator** | Translation using multiple APIs |

---

## 👁️ 7. COMPUTER VISION

| Library | Description |
|---|---|
| **OpenCV (cv2)** | THE computer vision library — image/video processing |
| **Pillow (PIL)** | Image processing — resize, crop, filter |
| **scikit-image** | Image processing algorithms |
| **imageio** | Read/write images and videos |
| **Albumentations** | Fast image augmentation for deep learning |
| **torchvision** | Vision datasets, transforms for PyTorch |
| **timm** | PyTorch Image Models — pretrained vision models |
| **Detectron2** | Facebook's object detection framework |
| **YOLO (ultralytics)** | Real-time object detection — YOLOv8/v11 |
| **MediaPipe** | Google's cross-platform ML for vision |
| **DeepFace** | Facial analysis — recognition, emotion, age |
| **face_recognition** | Simple face recognition library |
| **supervision** | Computer vision annotation and utilities |
| **kornia** | Differentiable computer vision for PyTorch |
| **MMDetection** | Object detection toolbox |

---

## 🔊 8. AUDIO & SPEECH

| Library | Description |
|---|---|
| **librosa** | Audio analysis — MFCCs, spectrograms |
| **pyaudio** | Audio I/O |
| **soundfile** | Read/write audio files |
| **SpeechRecognition** | Speech to text |
| **pyttsx3** | Text to speech (offline) |
| **gTTS** | Google Text-to-Speech |
| **TTS (Coqui)** | Deep learning TTS models |
| **Whisper (OpenAI)** | State-of-the-art speech recognition |
| **pyannote.audio** | Speaker diarization |
| **demucs** | Audio source separation (stem splitting) |
| **pydub** | Audio manipulation — slicing, effects |
| **audiomentations** | Audio augmentation |

---

## 🗄️ 9. DATABASES & ORMs

### SQL / Relational
| Library | Description |
|---|---|
| **SQLAlchemy** | THE Python ORM — works with PostgreSQL, MySQL, SQLite |
| **Alembic** | Database migrations for SQLAlchemy |
| **Peewee** | Lightweight ORM |
| **Tortoise ORM** | Async ORM for Python |
| **GINO** | Async ORM built on SQLAlchemy Core |
| **databases** | Async database access |
| **records** | SQL queries that return friendly data |
| **psycopg2** | PostgreSQL adapter |
| **psycopg3** | Async PostgreSQL adapter |
| **PyMySQL** | MySQL connector |
| **sqlite3** | Built-in SQLite interface |

### NoSQL
| Library | Description |
|---|---|
| **PyMongo** | MongoDB official driver |
| **Motor** | Async MongoDB driver |
| **MongoEngine** | ODM for MongoDB |
| **redis-py** | Redis client |
| **aioredis** | Async Redis client |
| **cassandra-driver** | Apache Cassandra driver |
| **elasticsearch-py** | Elasticsearch client |
| **Neo4j (py2neo)** | Graph database driver |
| **influxdb-client** | Time-series database client |

---

## ⚡ 10. ASYNC & CONCURRENCY

| Library | Description |
|---|---|
| **asyncio** | Built-in async I/O framework |
| **aiohttp** | Async HTTP client/server |
| **httpx** | Modern async HTTP client |
| **trio** | Alternative async framework — cleaner API |
| **anyio** | Async compatibility layer |
| **uvloop** | Ultra-fast asyncio event loop |
| **concurrent.futures** | Built-in thread/process pool |
| **multiprocessing** | Built-in parallel processing |
| **threading** | Built-in threading |
| **Celery** | Distributed task queue — background jobs |
| **RQ (Redis Queue)** | Simple job queue with Redis |
| **Dramatiq** | Background task processing |
| **APScheduler** | Advanced Python Scheduler — cron jobs |
| **Huey** | Lightweight task queue |
| **Ray** | Distributed computing framework |
| **Dask** | Parallel DataFrame + distributed computing |
| **Joblib** | Parallel loops and caching |

---

## 🌍 11. HTTP, NETWORKING & WEB SCRAPING

### HTTP Clients
| Library | Description |
|---|---|
| **requests** | THE Python HTTP library |
| **httpx** | Async-capable modern HTTP client |
| **urllib3** | HTTP client (underpins requests) |
| **aiohttp** | Async HTTP client |
| **grequests** | Async requests with gevent |

### Web Scraping
| Library | Description |
|---|---|
| **BeautifulSoup4 (bs4)** | HTML/XML parsing — simplest scraping |
| **Scrapy** | Full web scraping framework |
| **Selenium** | Browser automation — scraping JS-heavy sites |
| **Playwright** | Modern browser automation (better than Selenium) |
| **Playwright-asyncio** | Async Playwright |
| **Pyppeteer** | Headless Chrome in Python |
| **MechanicalSoup** | Form filling + scraping |
| **lxml** | Fast XML/HTML parsing |
| **httpx + parsel** | Fast + XPath/CSS selectors |
| **Splash** | JS rendering for Scrapy |

### Networking
| Library | Description |
|---|---|
| **socket** | Built-in low-level networking |
| **paramiko** | SSH2 protocol — remote server access |
| **Fabric** | SSH command execution and deployment |
| **scapy** | Packet crafting and network analysis |
| **pyshark** | Wireshark Python wrapper |
| **nmap (python-nmap)** | Network scanning |
| **dpkt** | Packet creation and parsing |
| **impacket** | Network protocol libraries |
| **netmiko** | Network device automation via SSH |
| **napalm** | Network automation framework |
| **websockets** | WebSocket client/server |
| **websocket-client** | WebSocket client |
| **pyzmq** | ZeroMQ bindings — messaging |

---

## 🔒 12. SECURITY & CRYPTOGRAPHY

| Library | Description |
|---|---|
| **cryptography** | THE crypto library — AES, RSA, hashing |
| **bcrypt** | Password hashing |
| **passlib** | Password hashing framework |
| **PyJWT** | JSON Web Tokens |
| **python-jose** | JWT + JWE + JWS |
| **PyCryptodome** | Cryptographic algorithms |
| **ssl** | Built-in TLS/SSL |
| **hashlib** | Built-in hashing — MD5, SHA256 |
| **hmac** | Built-in HMAC |
| **secrets** | Cryptographically strong random numbers |
| **pyOpenSSL** | OpenSSL bindings |
| **Bandit** | Security linting for Python code |
| **Safety** | Dependency vulnerability checking |
| **python-owasp-zap-v2.4** | OWASP ZAP automation |
| **sqlmap** | SQL injection testing (ethical hacking) |
| **pwntools** | CTF + exploit development |

---

## 🧪 13. TESTING

| Library | Description |
|---|---|
| **pytest** | THE Python testing framework |
| **unittest** | Built-in testing framework |
| **pytest-asyncio** | Async test support |
| **pytest-cov** | Code coverage reporting |
| **pytest-mock** | Mocking for pytest |
| **pytest-xdist** | Parallel test execution |
| **factory_boy** | Test fixture factories |
| **Faker** | Generate fake data for tests |
| **hypothesis** | Property-based testing |
| **responses** | Mock HTTP requests in tests |
| **httpretty** | HTTP mocking |
| **freezegun** | Mock datetime in tests |
| **locust** | Load testing — HTTP performance |
| **tox** | Testing in multiple environments |
| **coverage.py** | Code coverage measurement |
| **mypy** | Static type checking |
| **pyright** | Type checking by Microsoft |

---

## 🖥️ 14. GUI & DESKTOP APPLICATIONS

| Library | Description |
|---|---|
| **Tkinter** | Built-in GUI toolkit |
| **PyQt5 / PyQt6** | Qt bindings — rich desktop apps |
| **PySide6** | Official Qt for Python |
| **wxPython** | Cross-platform GUI toolkit |
| **Kivy** | Multi-touch GUI — mobile-ready |
| **Dear PyGui** | GPU-accelerated GUI |
| **PySimpleGUI** | Simple wrapper over Tkinter/Qt |
| **customtkinter** | Modern Tkinter with themes |
| **Eel** | Python + HTML/JS GUI |
| **pywebview** | Web-based GUI with native window |
| **flet** | Flutter-powered Python GUI |
| **toga** | Native-looking cross-platform GUI |
| **GTK (PyGObject)** | GTK3/4 bindings for Python |

---

## 📁 15. FILE HANDLING & I/O

| Library | Description |
|---|---|
| **os** | Built-in OS interface |
| **pathlib** | Object-oriented file paths |
| **shutil** | High-level file operations |
| **glob** | Pattern-based file matching |
| **watchdog** | Monitor filesystem changes |
| **openpyxl** | Read/write Excel files (.xlsx) |
| **xlrd / xlwt** | Read/write old Excel files (.xls) |
| **pandas (Excel)** | Read/write Excel, CSV, JSON |
| **python-docx** | Read/write Word documents |
| **PyPDF2 / pypdf** | PDF reading and manipulation |
| **reportlab** | Generate PDFs programmatically |
| **pdfplumber** | Extract text/tables from PDFs |
| **python-pptx** | Create/edit PowerPoint files |
| **csv** | Built-in CSV reader/writer |
| **json** | Built-in JSON parser |
| **yaml (PyYAML)** | YAML file parsing |
| **toml (tomllib)** | TOML config file parsing |
| **configparser** | INI config file parser |
| **h5py** | HDF5 file format |
| **netCDF4** | NetCDF scientific data format |
| **zarr** | Chunked, compressed N-D arrays |
| **zipfile** | Built-in ZIP file handling |
| **tarfile** | Built-in TAR file handling |

---

## 🤝 16. API CLIENTS & INTEGRATIONS

| Library | Description |
|---|---|
| **boto3** | AWS SDK for Python |
| **google-cloud-*` | Google Cloud SDK libraries |
| **azure-sdk** | Microsoft Azure SDK |
| **stripe** | Stripe payment API |
| **razorpay** | Razorpay payment API |
| **twilio** | SMS and voice API |
| **sendgrid** | Email API |
| **slack-sdk** | Slack Bot API |
| **discord.py** | Discord bot framework |
| **python-telegram-bot** | Telegram Bot API |
| **tweepy** | Twitter / X API |
| **praw** | Reddit API |
| **PyGithub** | GitHub API |
| **google-api-python-client** | All Google APIs |
| **google-auth** | Google OAuth |
| **facebook-sdk** | Facebook Graph API |
| **spotipy** | Spotify Web API |
| **yt-dlp** | YouTube video downloading |
| **pytube** | YouTube API |
| **instaloader** | Instagram data download |
| **shopifyapi** | Shopify API |

---

## 🔧 17. DEVOPS, CLI & AUTOMATION

### CLI Tools
| Library | Description |
|---|---|
| **argparse** | Built-in CLI argument parsing |
| **click** | Composable CLI creation |
| **typer** | Modern CLI with type hints |
| **rich** | Beautiful terminal output — colors, tables, progress |
| **textual** | TUI (Terminal UI) framework |
| **Prompt Toolkit** | Interactive command line tools |
| **Inquirer** | Interactive CLI prompts |
| **tqdm** | Progress bars |
| **alive-progress** | Animated progress bars |
| **colorama** | Cross-platform colored terminal text |
| **tabulate** | Pretty-print tables in terminal |
| **loguru** | Better logging |
| **structlog** | Structured logging |

### Automation & DevOps
| Library | Description |
|---|---|
| **subprocess** | Built-in — run shell commands |
| **invoke** | Python task runner |
| **Fabric** | Remote server automation via SSH |
| **Ansible (Python API)** | Infrastructure automation |
| **SaltStack** | Infrastructure management |
| **Nox** | Automation across Python versions |
| **pre-commit** | Git hooks framework |
| **cookiecutter** | Project template generator |
| **Paver** | Build tool |
| **PyAutoGUI** | Desktop automation — mouse, keyboard |
| **pygetwindow** | Window management |
| **keyboard** | Keyboard hook and control |
| **mouse** | Mouse hook and control |
| **pyperclip** | Clipboard access |
| **schedule** | Simple job scheduling |
| **APScheduler** | Advanced scheduler |

---

## 📦 18. SERIALIZATION & DATA FORMATS

| Library | Description |
|---|---|
| **pickle** | Built-in Python object serialization |
| **json** | Built-in JSON |
| **msgpack** | Fast binary serialization |
| **protobuf** | Google Protocol Buffers |
| **avro** | Apache Avro serialization |
| **orjson** | Ultra-fast JSON library |
| **ujson** | Ultra-fast JSON |
| **marshmallow** | Object serialization/deserialization |
| **cattrs** | Structuring/unstructuring of objects |
| **dataclasses-json** | JSON for dataclasses |

---

## ☁️ 19. CLOUD, DEPLOYMENT & INFRASTRUCTURE

| Library | Description |
|---|---|
| **boto3** | AWS — S3, EC2, Lambda, DynamoDB, etc. |
| **google-cloud-storage** | Google Cloud Storage |
| **azure-storage-blob** | Azure Blob Storage |
| **Pulumi (Python SDK)** | Infrastructure as Code |
| **Terraform (Python)** | via python-terraform |
| **docker (docker-py)** | Docker SDK for Python |
| **kubernetes (client)** | Kubernetes Python client |
| **paramiko** | SSH connections |
| **Fabric** | Deploy to remote servers |
| **Ansible** | Config management |
| **PyYAML** | Parse Kubernetes/Docker YAML files |
| **Pydantic Settings** | Environment configuration |
| **python-dotenv** | Load .env files |
| **dynaconf** | Configuration management |
| **sentry-sdk** | Error monitoring |
| **datadog** | Monitoring and analytics |
| **prometheus-client** | Metrics exporting |
| **opentelemetry** | Observability — traces, metrics, logs |

---

## 🔄 20. MESSAGE QUEUES & STREAMING

| Library | Description |
|---|---|
| **Celery** | Distributed task queue |
| **kombu** | Messaging library (used by Celery) |
| **pika** | RabbitMQ client |
| **kafka-python** | Apache Kafka client |
| **confluent-kafka** | High-performance Kafka client |
| **faust** | Stream processing with Kafka |
| **nats.py** | NATS messaging system |
| **aio-pika** | Async RabbitMQ client |

---

## 🔬 21. SCIENTIFIC & ENGINEERING

| Library | Description |
|---|---|
| **SciPy** | Scientific computing |
| **SymPy** | Symbolic math |
| **NumPy** | Numerical computing |
| **Astropy** | Astronomy and astrophysics |
| **BioPython** | Bioinformatics |
| **RDKit** | Cheminformatics |
| **Pyomo** | Optimization modeling |
| **CVXPY** | Convex optimization |
| **NetworkX** | Graph theory and network analysis |
| **igraph** | Fast graph analysis |
| **FEniCS** | Finite element analysis |
| **simpy** | Discrete-event simulation |
| **mesa** | Agent-based modeling |
| **pint** | Physical units handling |
| **uncertainties** | Uncertainty calculations |
| **control** | Control systems |

---

## 🎮 22. GAME DEVELOPMENT

| Library | Description |
|---|---|
| **Pygame** | 2D game development |
| **Arcade** | Modern 2D game framework |
| **Panda3D** | 3D game engine |
| **pyglet** | Windowing and multimedia |
| **Pyxel** | Retro game engine |
| **Ren'Py** | Visual novel engine |
| **Godot (GDScript/Python)** | 3D/2D game engine with Python-like scripting |

---

## 📡 23. IOT & HARDWARE (Useful for your Arduino background!)

| Library | Description |
|---|---|
| **pyserial** | Serial communication (Arduino!) |
| **MicroPython** | Python for microcontrollers |
| **CircuitPython** | Python for Adafruit boards |
| **RPi.GPIO** | Raspberry Pi GPIO control |
| **gpiozero** | Simple GPIO interface |
| **bleak** | Bluetooth Low Energy |
| **pyModbus** | Modbus protocol |
| **paho-mqtt** | MQTT for IoT messaging |
| **pyperclip** | Clipboard (useful in desktop automation) |
| **openocd** | Open On-Chip Debugger |

---

## 📐 24. CODE QUALITY & DEVELOPER TOOLS

### Formatters & Linters
| Library | Description |
|---|---|
| **black** | Opinionated code formatter |
| **ruff** | Ultra-fast linter + formatter (Rust-backed) |
| **flake8** | PEP8 linting |
| **pylint** | Comprehensive linting |
| **isort** | Sort imports |
| **autopep8** | Auto PEP8 fixer |
| **mypy** | Static type checking |
| **pyright** | Type checking by Microsoft |
| **pyflakes** | Error detection |
| **bandit** | Security linting |

### Documentation
| Library | Description |
|---|---|
| **Sphinx** | THE Python documentation generator |
| **MkDocs** | Markdown-based docs |
| **pdoc** | Auto-generate API docs |
| **pydoc** | Built-in documentation |
| **mkdocstrings** | Auto API docs in MkDocs |

### Package Management
| Library | Description |
|---|---|
| **pip** | Standard package manager |
| **poetry** | Dependency + packaging management |
| **pipenv** | Virtualenv + pip management |
| **uv** | Ultra-fast pip replacement (Rust-backed) |
| **conda** | Scientific Python package manager |
| **virtualenv** | Virtual environments |
| **pyenv** | Python version management |
| **nox** | Multi-environment automation |

---

## 🧩 25. UTILITIES & MISCELLANEOUS

| Library | Description |
|---|---|
| **itertools** | Built-in — combinatorics, iterators |
| **functools** | Built-in — higher-order functions |
| **collections** | Built-in — OrderedDict, Counter, deque |
| **dataclasses** | Built-in — clean data classes |
| **typing** | Built-in — type hints |
| **abc** | Built-in — abstract base classes |
| **enum** | Built-in — enumerations |
| **datetime** | Built-in — date/time handling |
| **calendar** | Built-in — calendar operations |
| **math** | Built-in — mathematical functions |
| **decimal** | Precise decimal arithmetic |
| **fractions** | Rational number arithmetic |
| **random** | Built-in — random numbers |
| **copy** | Built-in — deep/shallow copy |
| **gc** | Built-in — garbage collector |
| **sys** | Built-in — system-specific |
| **platform** | Built-in — platform info |
| **contextlib** | Built-in — context managers |
| **traceback** | Built-in — exception info |
| **warnings** | Built-in — warning control |
| **logging** | Built-in — logging framework |
| **loguru** | Advanced logging with colors |
| **pendulum** | Better datetime handling |
| **arrow** | Easy datetime manipulation |
| **humanize** | Human-readable values |
| **more-itertools** | Extended itertools |
| **toolz** | Functional programming utilities |
| **cytoolz** | Fast Cython version of toolz |
| **attrs** | Better classes with less boilerplate |
| **cattrs** | Attrs companion for conversion |
| **cachetools** | Caching utilities |
| **diskcache** | Persistent disk cache |
| **python-magic** | Detect file type |
| **chardet** | Detect character encoding |
| **colorlog** | Colored logging |
| **prettytable** | ASCII table formatter |
| **box (python-box)** | Dot-notation dictionary access |
| **dynaconf** | Dynamic configuration |
| **pint** | Physical units |
| **uuid** | Built-in UUID generation |
| **hashlib** | Built-in hashing |
| **base64** | Built-in Base64 encoding |
| **difflib** | Built-in — text differences |
| **textwrap** | Built-in — text wrapping |
| **string** | Built-in — string constants |
| **re** | Built-in — regex |
| **fnmatch** | Built-in — filename pattern matching |
| **zipimport** | Built-in — import from ZIP |

---

## 🗂️ MASTER CATEGORY OVERVIEW

| # | Domain | Key Libraries |
|---|---|---|
| 1 | Web Frameworks | Django, Flask, FastAPI, Tornado |
| 2 | Data Science | NumPy, Pandas, Polars, SciPy |
| 3 | Visualization | Matplotlib, Plotly, Seaborn, Streamlit |
| 4 | Machine Learning | Scikit-learn, XGBoost, LightGBM |
| 5 | Deep Learning | PyTorch, TensorFlow, Keras, JAX |
| 6 | NLP & LLMs | HuggingFace, LangChain, spaCy, OpenAI |
| 7 | Computer Vision | OpenCV, YOLO, MediaPipe, Pillow |
| 8 | Audio/Speech | librosa, Whisper, pyttsx3 |
| 9 | Databases & ORM | SQLAlchemy, PyMongo, Redis-py |
| 10 | Async | asyncio, Celery, Ray, aiohttp |
| 11 | Networking/Scraping | requests, Scrapy, Playwright, BeautifulSoup |
| 12 | Security & Crypto | cryptography, bcrypt, PyJWT |
| 13 | Testing | pytest, hypothesis, Faker |
| 14 | GUI/Desktop | PyQt6, Kivy, Tkinter, flet |
| 15 | File Handling | openpyxl, pypdf, python-docx |
| 16 | API Integrations | boto3, discord.py, tweepy |
| 17 | DevOps & CLI | click, rich, Fabric, PyAutoGUI |
| 18 | Serialization | orjson, protobuf, marshmallow |
| 19 | Cloud | boto3, GCP SDK, Azure SDK |
| 20 | Message Queues | Celery, kafka-python, pika |
| 21 | Scientific | SciPy, SymPy, NetworkX |
| 22 | Game Dev | Pygame, Arcade, Panda3D |
| 23 | IoT & Hardware | pyserial, RPi.GPIO, paho-mqtt |
| 24 | Code Quality | black, ruff, mypy, poetry |
| 25 | Utilities | itertools, functools, loguru, pendulum |

---

> [!TIP]
> **Don't try to learn everything at once.** Start with the domain you want to work in and go deep before going wide.

> [!NOTE]
> **For Web Development specifically**: Focus on → `FastAPI` or `Django` + `SQLAlchemy` + `Pydantic` + `aiohttp` + `celery` + `redis-py`

> [!IMPORTANT]
> **For AI/ML**: Focus on → `PyTorch` + `HuggingFace Transformers` + `LangChain` + `scikit-learn` + `pandas` + `NumPy`
