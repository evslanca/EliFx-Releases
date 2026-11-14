# EliFx — Audio Enhancer & Equalizer (Portable)

![Plataforma](https://img.shields.io/badge/Windows-10%20%2F%2011%20(64--bit)-0078D6?style=for-the-badge&logo=windows)
![Versao](https://img.shields.io/badge/Vers%C3%A3o-1.0.19-00D4FF?style=for-the-badge)
![Modo](https://img.shields.io/badge/Modo-Portable-10B981?style=for-the-badge)

Processador e equalizador de áudio em tempo real para **Windows 10 e Windows 11 (x64)**, com interface moderna de alto contraste, baixíssimo consumo de CPU/memória e funcionamento **100% portátil** (não precisa instalar).

---

## Download

| Arquivo | Descrição | Link |
| :--- | :--- | :--- |
| **`EliFx-Portable-v1.0.19-win64.zip`** | **Pacote completo (Recomendado)** — executável, presets de fábrica, fontes, modo portátil e instalador de driver virtual | [**Baixar Pacote Portable (.zip)**](https://github.com/evslanca/EliFx-Releases/releases/download/v1.0.19/EliFx-Portable-v1.0.19-win64.zip) |
| **`EliFx.exe`** | Executável avulso (sem dependências externas) | [**Baixar EliFx.exe**](https://github.com/evslanca/EliFx-Releases/releases/download/v1.0.19/EliFx.exe) |

> Todas as versões publicadas estão disponíveis na aba [**Releases**](https://github.com/evslanca/EliFx-Releases/releases).

---

## Principais Recursos

- **Equalizador Paramétrico / Gráfico Multi-bandas**: alterne instantaneamente entre **5, 10 ou 31 bandas** com botão **Zerar EQ**.
- **LEDs Reativos nos Potenciômetros e VUs Inteligentes**: LEDs nos vãos dos controles com **Peak-Hold + queda por gravidade** (rastro inteligente) no EQ, VU principal e visualizador de espectro.
- **Controle Rápido de Volume Geral e Mute**: acesso direto ao lado do botão ligar/desligar.
- **Presets Profissionais Inclusos**: 20 predefinições de fábrica (`Factsoft\`) + suporte a criação, edição, importação e exportação de presets personalizados.
- **Bandeja do Sistema (System Tray)**: menu completo com troca rápida de dispositivo de saída, presets, temas e opção *Sempre no topo*.
- **Otimizado para Baixo Consumo**: zero alocações por frame nos VUs, timers pausados automaticamente quando minimizado ou sem áudio e runtime estático embutido (sem precisar instalar Visual C++ Redistributable).

---

## Como Usar (Modo Portable)

1. Baixe e extraia **`EliFx-Portable-v1.0.19-win64.zip`** em qualquer pasta do computador ou pendrive.
2. Execute **`EliFx.exe`**.
3. O arquivo **`portable.flag`** já vem incluído: todas as suas configurações e presets salvos ficam armazenados dentro da pasta **`Data\`** ao lado do executável.

### Driver de Áudio Virtual (primeira vez em um PC novo)

Para que o Windows roteie o áudio pelo processador DSP do EliFx em um computador que ainda não tenha o driver instalado:

1. Execute **`Instalar-Driver-Audio.bat`** (clique duplo e aceite a permissão de Administrador / UAC).
2. Caso esteja usando em um PC emprestado e queira remover o driver depois, execute **`Remover-Driver-Audio.bat`**.

---

## Requisitos do Sistema

- **Sistema Operacional**: Windows 10 ou Windows 11 (64-bit / x64)
- **Dependências**: Nenhuma (runtime C++ embutido no executável)