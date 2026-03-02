# Transcritor de Voz com Python

Um projeto simples em Python que utiliza a biblioteca `SpeechRecognition` para capturar áudio do microfone e transcrevê-lo para texto em português.

## Funcionalidades

- Captura de áudio via microfone
- Transcrição automática usando o serviço da Google
- Suporte ao idioma português (pt-BR)
  
## Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedrolucasfonseca/Transcritor-de-Voz.git
   cd Transcritor-de-Voz
   ```

2. Instale as dependências:
   ```bash
   pip install SpeechRecognition
   pip install pyaudio
   ```

3. Execute o script:
   ```bash
   python transcritor_de_voz.py
   ```

## Funcionamento

- O script ajusta o microfone ao ruído ambiente.
- Grava o áudio por um tempo definido (padrão: 10 segundos).
- Utiliza o serviço de reconhecimento de voz da Google para transcrever o áudio.

## Requisitos

- Python 3.10 ou superior
- Microfone funcional
