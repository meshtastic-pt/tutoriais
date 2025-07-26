# 📚 Tutoriais Meshtastic PT

Este repositório reúne **tutoriais colaborativos** para o projeto [Meshtastic PT](https://meshtastic.pt) — uma comunidade portuguesa dedicada à utilização de rádios LoRa com o firmware [Meshtastic](https://meshtastic.org).

Através deste repositório, qualquer membro da comunidade pode contribuir com tutoriais passo-a-passo, guias de configuração, dicas avançadas ou imagens úteis. O conteúdo aqui criado será posteriormente publicado no site oficial.

> ✅ Este repositório **não contém o código-fonte do site**, apenas os tutoriais em formato Markdown.

---

## ✍️ Como contribuir

Contribuir é simples! Siga estes passos:

1. Faça um **fork** deste repositório para a sua conta GitHub.
2. Crie um **branch novo** para a sua contribuição:
   ```bash
   git checkout -b adicionar-tutorial-app-ios
   ```
3. Adicione ou edite os tutoriais na pasta `/tutoriais/`.
4. Se necessário, adicione imagens à pasta `/imagens/`.
5. Faça um commit com uma mensagem clara e envie um **Pull Request**.

Todas as contribuições serão revistas antes de serem aceites.

---

## 📂 Estrutura dos ficheiros

A estrutura do repositório é simples e organizada:

```
/
├── tutoriais/
│   ├── instalacao/
│   │   ├── 01_flashear-via-chrome.md
│   │   └── 02_instalar-app.md
│   ├── configuracao/
│   │   ├── android.md
│   │   └── ios.md
│   └── avancado/
│       └── mqtt_customizado.md
├── imagens/
│   ├── passo1_flash.png
│   └── configurar_app.png
├── README.md
└── CONTRIBUTING.md
```

- Tutoriais devem estar em formato `.md` (Markdown).
- Use nomes descritivos e, se necessário, ordenação numérica:  
  `01_configurar-nome-do-node.md`
- Imagens devem ser colocadas em `/imagens/` e referenciadas com caminho relativo no Markdown:
  ```markdown
  ![Exemplo](../../imagens/passo1_flash.png)
  ```

---

## 📌 Regras de escrita

- Utilize **português de Portugal**.
- Prefira linguagem clara, objetiva e técnica.
- Evite linguagem informal ou pessoal (ex: "tu", "vais").
- Divida o conteúdo com títulos `##`, `###`, listas e imagens.
- Adicione notas ou alertas importantes com blocos `>`, `⚠️`, `ℹ️`, etc.

### Exemplo:

```markdown
## Como ligar o dispositivo ao computador

1. Utilize um cabo USB de dados.
2. Certifique-se de que o dispositivo está em modo bootloader.

> ⚠️ Alguns cabos apenas carregam e não transmitem dados.
```

---

## 🤝 Ajuda e contacto

Se tiver dúvidas sobre como contribuir, abra uma **Issue** neste repositório ou contacte-nos através do [Grupo Telegram Meshtastic PT](https://t.me/comunidademeshtasticpt).

---

**Obrigado por contribuir!  
Juntos, tornamos o Meshtastic mais acessível para todos. 🇵🇹📡**
