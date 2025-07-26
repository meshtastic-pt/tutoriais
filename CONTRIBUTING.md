# Guia de Contribuição para Tutoriais Meshtastic PT

Obrigado pelo seu interesse em contribuir para os tutoriais da comunidade **Meshtastic PT**! Este repositório tem como objetivo reunir guias de instalação, configuração e utilização de dispositivos Meshtastic, escritos pela comunidade, para a comunidade.

Este documento explica como pode contribuir de forma clara e estruturada.

---

## 📌 Requisitos gerais

- Os tutoriais devem ser escritos em **português de Portugal**.
- Utilize **linguagem formal e objetiva**, adequada a documentação técnica.
- Evite informalidades como "tu", "teu", "vais" – prefira "o utilizador", "deverá", etc.
- Toda a contribuição deve ser feita através de **Pull Requests**, sujeita a revisão.

---

## 📂 Estrutura do projeto

Todos os tutoriais encontram-se na pasta:

/tutoriais/


Cada subpasta representa uma categoria:

- `/instalacao/` – Guias de instalação (firmware, app, etc.)
- `/configuracao/` – Tutoriais de configuração (app, MQTT, nomes, canais)
- `/avancado/` – Tópicos avançados (firmware customizado, rede mesh, etc.)

As imagens associadas devem ser guardadas em:

/imagens/


---

## ✍️ Formato dos tutoriais

- Cada tutorial deve ser um ficheiro `.md` (Markdown).
- Nomeie os ficheiros com letras minúsculas e separadores `_` ou numeração:
  - `01_flashear-via-chrome.md`
  - `configurar_app_android.md`
- Use títulos e subtítulos bem organizados:
  - `## Título principal`
  - `### Subtítulo`
  - `#### Passo` (se necessário)

---

## 🖼️ Imagens

- Guarde as imagens em `/imagens/`.
- Use nomes de ficheiros claros e descritivos:
  - `passo1_flash_chrome.png`
  - `app_android_configuracao.png`
- Referencie as imagens no tutorial com caminho relativo:
  ```markdown
  ![Instalar firmware](../../imagens/passo1_flash_chrome.png)
