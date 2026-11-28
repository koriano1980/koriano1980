# Mis repositorios, ordenados por categoría

Cada programa con su repositorio. Las copias (forks) apuntan al proyecto original.

## 🔍 Ingeniería inversa y clonar apps

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| rea | Hace ingeniería inversa con agentes de IA, desde el comportamiento de una app hasta sus binarios. | [koriano1980/rea](https://github.com/koriano1980/rea) | [morluto/rea](https://github.com/morluto/rea) |
| replica-skill | Once skills gratis de Claude para analizar una app, reconstruirla y probarla. | [koriano1980/replica-skill](https://github.com/koriano1980/replica-skill) | [Jakeschincariol/replica-skill](https://github.com/Jakeschincariol/replica-skill) |

## 🛡️ Ciberseguridad

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| AiSOC | Centro de seguridad con IA: junta alertas y las clasifica con agentes. | [koriano1980/AiSOC](https://github.com/koriano1980/AiSOC) | [beenuar/AiSOC](https://github.com/beenuar/AiSOC) |
| geo-recon | Consulta la ubicación aproximada y la reputación de una IP desde la terminal. | [koriano1980/geo-recon](https://github.com/koriano1980/geo-recon) | [radioactivetobi/geo-recon](https://github.com/radioactivetobi/geo-recon) |
| RedTeam-Tools | Catálogo de referencia (no es un paquete instalable: el repo solo trae un README) con 150+ herramientas y recursos de red teaming / hacking ético, organizados por fases. Cada entrada enlaza al proyecto original; el autor lo marca como informativo y educativo. | [koriano1980/RedTeam-Tools](https://github.com/koriano1980/RedTeam-Tools) | [A-poc/RedTeam-Tools](https://github.com/A-poc/RedTeam-Tools) |

## 🌍 Mapas / OSINT

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| gods-eye-view | Globo 3D en el navegador con vuelos, barcos, satélites, cámaras y otros datos públicos en vivo. Se instala en tu Mac y corre en local. | [koriano1980/gods-eye-view](https://github.com/koriano1980/gods-eye-view) | [bilawalsidhu/gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) |

## 🔒 Seguridad / Claude Code

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| SkillSpector | Escáner de NVIDIA que revisa skills de agentes de IA (Claude Code y otros) en busca de vulnerabilidades o código malicioso antes de instalarlas. | [koriano1980/SkillSpector](https://github.com/koriano1980/SkillSpector) | [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) |
| Claude-BugHunter | Kit de skills para Claude Code (MIT, de un tercero, no de Anthropic) para bug bounty autorizado: metodología, patrones de reportes públicos ya divulgados y plantillas para redactar informes. El reel de Nino Director lo muestra como “kit abierto” para buscar fallas fáciles en programas que pagan (p. ej. Meta Bug Bounty). Solo se usa en activos en alcance, con cuentas de prueba propias; no garantiza un pago. Corre en la Mac mini M4 porque ya tiene Claude Code. Antes de instalarlo, conviene revisarlo con SkillSpector. | [koriano1980/Claude-BugHunter](https://github.com/koriano1980/Claude-BugHunter) | [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter) |

## 🗺️ Claude Code / Grafo de código

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| graphify | Convierte un repositorio (código, docs, SQL, configs y PDFs) en un grafo de conocimiento que Claude Code u otro agente consulta en vez de releer todo el proyecto. El código se analiza en local con tree-sitter, sin vector store ni cuenta. Es gratis y open-source (Apache 2.0) y corre en la Mac mini M4 (Python 3.11.5+ y uv). El producto alojado en [graphify.com](https://graphify.com) es aparte (Free hasta 3 repos; Pro desde USD 10/mes anual). | [koriano1980/graphify](https://github.com/koriano1980/graphify) | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) |

## 🧭 Claude Code / Equipo de agentes

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| ECC | Sistema open-source (MIT) de Affaan Mustafa, ganador de un hackathon de Anthropic: convierte Claude Code (y también Codex, Cursor, OpenCode y OpenClaw) en un equipo con 72 agentes, 328 skills, 99 comandos, memoria unificada, instintos que aprenden de cómo trabajas, y AgentShield para revisar la seguridad del harness. El kit local es gratis (`npx ecc-universal@2.2.3 setup`; hace falta Node.js 18+, Git y Claude Code 2.1+). Corre en la Mac mini M4 (macOS es plataforma soportada). ECC Pro / GitHub App para repos privados cuesta USD 19/asiento/mes; no hace falta para usarlo en local. Instálalo solo del repo oficial o de [ecc.tools](https://ecc.tools), hay copias falsas. | [koriano1980/ECC](https://github.com/koriano1980/ECC) | [affaan-m/ECC](https://github.com/affaan-m/ECC) |

## 🛠️ Claude Code / Skills de ingeniería

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| skills | Colección oficial de Matt Pocock (MIT): skills pequeñas y componibles para Claude Code (también Codex, Copilot, Cursor y OpenCode). El flujo es entrevista → spec → tickets → código. La más usada es `/grill-me`: te interroga el plan hasta encontrar agujeros, sin escribir código. También trae `/to-spec`, `/to-tickets`, `/implement`, `/tdd` y `/grill-with-docs` (~27 skills). Gratis y open-source; se instala con `claude plugin install mattpocock-skills@claude-plugins-official` (se actualiza solo). Corre en la Mac mini M4 y en la MacBook Pro M4 porque ya tienen Claude Code. No pisa Graphify ni tu vault de Obsidian; no instales a la vez el plugin oficial y `npx skills` en el mismo agente, porque duplicaría las skills. | [koriano1980/skills](https://github.com/koriano1980/skills) | [mattpocock/skills](https://github.com/mattpocock/skills) |

## 🕷️ Extracción de datos web

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| Scrapling | Framework para extraer datos de páginas web públicas. | [koriano1980/Scrapling](https://github.com/koriano1980/Scrapling) | [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) |

## 🖥️ Productividad y computadoras

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| TwinDesk | Une tus computadoras y tu teléfono como un solo escritorio: pantallas, apps, archivos y portapapeles. | [koriano1980/TwinDesk](https://github.com/koriano1980/TwinDesk) | [InukaAsith/TwinDesk](https://github.com/InukaAsith/TwinDesk) |

## 🍏 Utilidades macOS

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| findphone | Localiza un iPhone u otro dispositivo Apple cercano por la señal Bluetooth, desde la terminal de tu Mac, cuando Buscar no está disponible. | [koriano1980/findphone](https://github.com/koriano1980/findphone) | [ben-z/findphone](https://github.com/ben-z/findphone) |

## 📱 iPhone / Widgets

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| att-usage-widget | Widget de Scriptable para ver el consumo de datos de AT&T en Estados Unidos (prepago o pospago). | [koriano1980/att-usage-widget](https://github.com/koriano1980/att-usage-widget) | Propio. AT&T US no tiene API pública; el post de BAIT/AT&T México no publicó repo. Lo más cercano para México es [amaynez/telcel-widget-agy](https://github.com/amaynez/telcel-widget-agy). |

## 📱 Agentes de IA / móvil

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| phone-harness | Deja que Claude Code u otro agente use tu iPhone o Android: toca, escribe y desplaza como tú, sin jailbreak ni app en el teléfono. En la Mac se conecta con iPhone Mirroring (iOS 18+) o con adb para Android. Usar tu propio móvil es gratis (MIT); la nube de iPhones/Androids es de pago. | [koriano1980/phone-harness](https://github.com/koriano1980/phone-harness) | [phone-harness/phone-harness](https://github.com/phone-harness/phone-harness) |
| mobile-mcp | Servidor MCP de Mobile Next (Apache 2.0) para que Claude Code, Codex, Gemini u otro cliente MCP controle un iPhone o Android: abre apps, pulsa, escribe, hace gestos, instala apps y automatiza pruebas. Funciona con simuladores, emuladores y dispositivos reales por USB. El uso local es gratis (`npx @mobilenext/mobile-mcp@latest`); [Mobile Next Cloud](https://mobilenext.ai) es opcional y de pago (Hobby gratis 10 min/día; Starter USD 29/mes). Corre en la Mac mini M4 y en la MacBook Pro M4 (hace falta Node.js 20+; el simulador de iOS necesita Xcode; Android usa adb). No reemplaza ECC, Graphify ni Obsidian: le da a Claude Code un teléfono para probar apps nativas. | [koriano1980/mobile-mcp](https://github.com/koriano1980/mobile-mcp) | [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) |

## 🚗 Autos / Tesla y Android Auto

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| custom-wraps | Plantillas oficiales de Tesla en PNG (512×512 a 1024×1024) para crear wraps personalizados y cargarlos en la vista 3D del carro desde la app de Tesla o por USB (Toybox → Paint Shop → Wraps). | [koriano1980/custom-wraps](https://github.com/koriano1980/custom-wraps) | [teslamotors/custom-wraps](https://github.com/teslamotors/custom-wraps) |
| AA-Experiments | Inspecciona y cambia los experimentos de Android Auto con LSPosed. | [koriano1980/AA-Experiments](https://github.com/koriano1980/AA-Experiments) | [HighwindBR/AA-Experiments](https://github.com/HighwindBR/AA-Experiments) |

## 🧠 IA local / LLM

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| koboldcpp | Corre modelos de IA (GGUF) en tu propia computadora, con chat, imágenes, voz y un agente, en un solo ejecutable. | [koriano1980/koboldcpp](https://github.com/koriano1980/koboldcpp) | [LostRuins/koboldcpp](https://github.com/LostRuins/koboldcpp) |
| Nemotron | Recetas, guías y ejemplos de NVIDIA para entrenar y usar la familia Nemotron. Incluye Nemotron 3 Ultra (550 mil millones de parámetros, 1 millón de tokens de contexto). Se prueba gratis en [build.nvidia.com](https://build.nvidia.com); correr Ultra en local requiere un clúster, no una Mac. | [koriano1980/Nemotron](https://github.com/koriano1980/Nemotron) | [NVIDIA-NeMo/Nemotron](https://github.com/NVIDIA-NeMo/Nemotron) |
| tinker-cookbook (Inkling 2 Mini) | Recetas oficiales de Thinking Machines Lab para usar y entrenar la familia Inkling. Inkling 2 Mini es un modelo open-weight (Apache 2.0) multimodal de 26,4B parámetros (looped transformer) que reutiliza capas para razonar mejor; corre en local en Mac con llama.cpp, MLX u Ollama (GGUF Q4 ~16,6 GB; se recomiendan 32 GB de memoria unificada). Pesas: [Hugging Face](https://huggingface.co/thinkingmachines/Inkling-2-Mini). | [koriano1980/tinker-cookbook](https://github.com/koriano1980/tinker-cookbook) | [thinking-machines-lab/tinker-cookbook](https://github.com/thinking-machines-lab/tinker-cookbook) |
| clover-35b-guia-8gb (Clover 35B-A3B) | Guía en español para correr Clover-35B-A3B-Preview, un modelo open-weight de DiffuSpace (Apache 2.0): MoE de 35B parámetros (~3B activos por token) con 128K de contexto. El reel lo prueba en Windows con una RTX 5060 Laptop de 8 GB y 32 GB de RAM (~31–34 tok/s); el GGUF Q4_K_M pesa ~21,4 GiB y no cabe solo en VRAM. La guía es MIT. En la Mac mini M4 se puede intentar con llama.cpp (Metal, b12052+), pero hace falta memoria unificada holgada (idealmente 32 GB o más). Pesos: [Hugging Face](https://huggingface.co/Diffuspace/Clover-35B-A3B-Preview). | [koriano1980/clover-35b-guia-8gb](https://github.com/koriano1980/clover-35b-guia-8gb) | [RicardoBertran/clover-35b-guia-8gb](https://github.com/RicardoBertran/clover-35b-guia-8gb) |
| HyperQwen | Motor open-source (Apache 2.0) para servir Qwen3.8-27B muy rápido en una sola GPU NVIDIA de 24 GB, con vLLM y decodificación especulativa (DFlash/MTP). En el reel de Andy Cufari, el mismo modelo y el mismo prompt en dos RTX 3090: Ollama ~28 tok/s vs HyperQwen >250 tok/s al corregir código (casi 9×; ~3× en texto nuevo; ~4× frente a Ollama con su ayudante MTP). Las respuestas salen idénticas. No corre de forma nativa en la Mac mini M4: necesita CUDA (Ampere o más nueva, 24 GB). La Mac solo puede usarse como cliente de un servidor NVIDIA. | [koriano1980/HyperQwen](https://github.com/koriano1980/HyperQwen) | [syv-ai/HyperQwen](https://github.com/syv-ai/HyperQwen) |

## 🧪 Simulación social / predicción

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| MiroFish | Simula una red social con miles de agentes de IA para probar una idea y te entrega un informe; luego puedes entrevistar a esos agentes. Se instala en la Mac. Necesita una clave de Zep Cloud y un modelo de lenguaje (Ollama en local o una API). Guía: [INSTALAR-MAC.md](https://github.com/koriano1980/MiroFish/blob/main/INSTALAR-MAC.md). | [koriano1980/MiroFish](https://github.com/koriano1980/MiroFish) | [666ghj/MiroFish](https://github.com/666ghj/MiroFish) |
| Sybil-Swarm | Panel de clientes sintéticos: decenas de personas simuladas con IA evalúan un producto (compra, precio, objeciones) y entregan un informe con puntaje. Instalado en la Mac mini con Ollama local, sin APIs pagas; lo usan los bots de Amazon y Hotmart para buscar productos ganadores. | [koriano1980/Sybil-Swarm](https://github.com/koriano1980/Sybil-Swarm) | [nghiahsgs/Sybil-Swarm](https://github.com/nghiahsgs/Sybil-Swarm) |

## 🎬 Video e IA

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| hyperframes | Editor de video para agentes de IA (HyperFrames Studio): le escribes un mensaje y arma o edita la línea de tiempo; también se edita a mano y se exporta a MP4 en tu Mac. | [koriano1980/hyperframes](https://github.com/koriano1980/hyperframes) | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) |
| AI-Youtube-Shorts-Generator | Convierte un video largo de YouTube en shorts verticales listos para TikTok, Reels y Shorts, con transcripción e IA. | [koriano1980/AI-Youtube-Shorts-Generator](https://github.com/koriano1980/AI-Youtube-Shorts-Generator) | [Anil-matcha/AI-Youtube-Shorts-Generator](https://github.com/Anil-matcha/AI-Youtube-Shorts-Generator) |

## 👁️ 3D / Three.js

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| procedural-eye | Demo en three.js de un ojo humano hiperrealista y procedural, con iris, párpados, luz y modo foto. | [koriano1980/procedural-eye](https://github.com/koriano1980/procedural-eye) | [rock-biter/procedural-eye](https://github.com/rock-biter/procedural-eye) |

## 🧩 3D / Simuladores

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| teardown | Skill de Claude Code que arma un simulador 3D desmontable de cualquier máquina en una sola página HTML. | [koriano1980/teardown](https://github.com/koriano1980/teardown) | [elvarofficial/teardown](https://github.com/elvarofficial/teardown) |

## 🎮 Juegos / Mods

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| universal-modder | Skills y herramientas para que un agente de IA cree mods de casi cualquier juego de PC que tengas. | [koriano1980/universal-modder](https://github.com/koriano1980/universal-modder) | [rehan-remade/universal-modder](https://github.com/rehan-remade/universal-modder) |

## 🎨 Gráficos

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| draw-beautiful | Skill de Claude Code que construye un objeto en 3D, lo ilumina y lo convierte en un grabado con líneas, al estilo de un billete. | [koriano1980/draw-beautiful](https://github.com/koriano1980/draw-beautiful) | [bumicodes/draw-beautiful](https://github.com/bumicodes/draw-beautiful) |

## 🌐 Web / Portafolios

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| xikhar.github.io | Sitio de GitHub Pages con compilaciones publicadas (incluye el proyecto Sumiro). | [koriano1980/xikhar.github.io](https://github.com/koriano1980/xikhar.github.io) | [xikhar/xikhar.github.io](https://github.com/xikhar/xikhar.github.io) |

## 💰 Cripto / DeFi

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| Uniswap v3-core | Contratos del exchange descentralizado Uniswap v3: los pools donde pones dos monedas (por ejemplo cbBTC y USDC) y cobras parte de la comisión de cada intercambio. Es código de blockchain, no una app para instalar en la Mac. | [koriano1980/v3-core](https://github.com/koriano1980/v3-core) | [Uniswap/v3-core](https://github.com/Uniswap/v3-core) |

## 📈 Trading / Claude Code

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| day-trader-skill | 11 skills de Claude Code (MIT, de Jake Schincariol) para day trading: escanea gráficos, sigue noticias, cronometra entradas y salidas, y una Time Machine que simula el resto de la sesión 10.000 veces antes de arriesgar un dólar. Gratis, sin registro, Python estándar y datos públicos (Yahoo Finance, SEC). El paper trading es el valor por defecto; `/trader-broker` se conecta al MCP de Alpaca (cuenta paper por defecto) y no envía ninguna orden sin un “sí” explícito. Corre en la Mac mini M4 (ya tiene Claude Code y Python 3.8+). No es consejo financiero ni garantiza ganancias. | [koriano1980/day-trader-skill](https://github.com/koriano1980/day-trader-skill) | [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) |

## 🤖 Proyectos propios / Agentes

| Programa | Qué hace | Mi copia | Original |
|---|---|---|---|
| enjambre-agentes-mac | App nativa para Mac: varios agentes locales y en línea que controlan la Mac por voz o a distancia, con cursores animados. | [koriano1980/enjambre-agentes-mac](https://github.com/koriano1980/enjambre-agentes-mac) | Propio. |

## 🧾 Identificados, sin repositorio público

Herramientas vistas en reels cuyo código no está publicado. No hay fork porque no existe un repo oficial.

| Programa | Qué hace | Sitio | Notas |
|---|---|---|---|
| Pazi | Agentes de IA en la web que, a partir de una idea, arman el negocio: sitio, anuncios, correos y redes. | [pazi.ai](https://pazi.ai/) | No hay repositorio oficial público. |
| ARGOS ATLAS | Mapa mundial en el navegador con cámaras, vuelos, barcos e infraestructura, sin instalar nada. | [argosatlas.com](https://argosatlas.com/) | No hay repositorio oficial público. Lo más cercano de código abierto es [gods-eye-view](https://github.com/bilawalsidhu/gods-eye-view) (arriba). |
| PagePilot | Constructor de páginas de producto con IA para tiendas de Shopify. | [pagepilot.ai](https://pagepilot.ai/) | No hay repositorio oficial público. |

## 💡 Planes y proyectos propios (privados)

| Proyecto | Qué es |
|---|---|
| [plan-negocio-ia-mac-m4](https://github.com/koriano1980/plan-negocio-ia-mac-m4) | Plan paso a paso para ganar dinero o ahorrar tiempo con IA desde la Mac mini M4. |
