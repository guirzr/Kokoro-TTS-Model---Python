# Kokoro Text-to-Speech

Projeto Python para converter um texto em áudio utilizando a biblioteca **Kokoro TTS**.

## Como funciona

O programa:

1. Solicita um texto ao usuário.
2. Envia o texto para o modelo Kokoro.
3. Gera o áudio utilizando a voz `af_alloy`.
4. Junta todos os trechos de áudio.
5. Salva o resultado no arquivo `audio_completo.wav`.

## Imports

- Python 3.10 ou superior
- Biblioteca Kokoro
- NumPy
- SoundFile

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

Instale as dependências:

```bash
pip install kokoro soundfile numpy
```

## Executando

Execute o arquivo:


No cmd
```
uv run kokoro.py 
```


Digite o texto desejado quando solicitado:

```text
Escreva um texto:
```

Exemplo:

```text
Escreva um texto:
Olá! Este é um teste utilizando o Kokoro.
```

## Saída

Após a execução será criado o arquivo:

```
audio_completo.wav
```

Esse arquivo conterá o áudio correspondente ao texto informado.

## Estrutura do projeto

```
.
├── kokoro_basic.py
├── audio_completo.wav
└── README.md
```

## Tecnologias

- Python
- Kokoro TTS
- NumPy
- SoundFile

