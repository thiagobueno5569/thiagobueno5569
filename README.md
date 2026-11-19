<h1 align="center">Olá, eu sou o Thiago 👋</h1>

<p align="center">
  Estudante de <b>Engenharia Elétrica na UFSJ</b> (São João del-Rei, MG).<br/>
  Gosto de fazer IA rodar onde ela "não deveria caber": em placa de vídeo comum, em webcam, em tablet velho na parede.
</p>

<p align="center"><i>🇬🇧 Electrical Engineering student in Brazil. I build local AI: my main project, <a href="https://github.com/thiagobueno5569/fatiador"><b>Fatiador</b></a>, runs giant Mixture-of-Experts LLMs on a consumer GPU.</i></p>

---

## 🔪 Projeto principal: [Fatiador](https://github.com/thiagobueno5569/fatiador)

**Rodar modelos de IA gigantes numa placa de vídeo comum, carregando só os especialistas do assunto da conversa.**

Os modelos Mixture-of-Experts são cortados em fatias por assunto: um núcleo comum mais os especialistas que aquele assunto realmente usa. Testei tudo num PC doméstico (RTX 2060 com 6 GB):

| | Resultado |
|---|---|
| ⚡ Qwen3-30B em fatias de 5,4 GB | **3,5× mais rápido** (55,9 tokens/s) |
| 🎯 Fatia de 64 especialistas | só **1% a 18% pior** que o modelo inteiro, com metade do tamanho |
| 🧠 Super-especialistas | detector automático achou os 3 especialistas (de 6.144) sem os quais o modelo quebra |
| 🐘 gpt-oss-120b (63 GB) | rodando num PC com 32 GB de RAM |

## 🛠️ Outros projetos

| Projeto | O que é |
|---|---|
| [apuracao-2026](https://github.com/thiagobueno5569/apuracao-2026) | Site de apuração ao vivo do 2º turno de 2026 com dados do TSE |
| [painel-parede](https://github.com/thiagobueno5569/painel-parede) | Painel para tablet na parede: agenda, aulas e lembretes do dia, com back-end no Google Apps Script |
| [ia](https://github.com/thiagobueno5569/ia) | Detecção de objetos em tempo real pela webcam com YOLOv3 e OpenCV |
| [Solar_System-Simulator](https://github.com/thiagobueno5569/Solar_System-Simulator) | Sistema solar simulado com a lei da gravitação universal (Python + Matplotlib) |

## 🧰 Ferramentas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=flat&logo=meta&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

## 🔭 Interesses

IA local e eficiente (Mixture-of-Experts, quantização, inferência em hardware comum) · visão computacional · eletrônica e comunicação serial com microcontroladores.
