# 🎮 Sistema de Quiz Dinâmico em Python

Sistema de quiz desenvolvido em Python capaz de adaptar automaticamente seu comportamento com base no conteúdo do arquivo de entrada.

A aplicação possui dois modos de execução:

- 🔹 **Modo Padrão** – Executa como um quiz tradicional.
- 🔹 **Modo LIS (RPG)** – Ativado automaticamente quando identificadores específicos são detectados no arquivo `quiz.txt`, transformando o quiz em uma experiência temática de batalha contra os "Monstros da Procrastinação".

---

## 🧠 Conceito do Projeto

O sistema foi projetado para:

- Ler perguntas dinamicamente a partir de um arquivo externo
- Funcionar corretamente independentemente do tema das questões
- Detectar padrões específicos no conteúdo do arquivo
- Alterar o comportamento do programa automaticamente com base nessa detecção

Desde que o arquivo siga a estrutura esperada e esteja nomeado como `quiz.txt`, o sistema executará corretamente.

---

## 📂 Funcionamento

1. O programa lê o arquivo `quiz.txt`.
2. Analisa o conteúdo em busca de identificadores específicos.
3. Define automaticamente o modo de execução.
4. Executa o quiz no modo correspondente (Padrão ou LIS).

---

## 🎭 Ativação do Modo LIS

O **Modo LIS** recebe esse nome a partir das iniciais das criadoras do projeto.

Ele é ativado automaticamente quando o sistema identifica, no arquivo `quiz.txt`, os seguintes nomes:

- Laura  
- Isabela  
- Sofia  

Ao detectar esses identificadores, o programa executa o quiz no modo temático (RPG).

### 🔄 Como executar no modo padrão

Para rodar o sistema no **Modo Padrão**, basta remover os nomes citados do final do arquivo `quiz.txt`.

Sem a presença desses identificadores, o sistema executará automaticamente a versão tradicional do quiz.

---

## ⚙️ Tecnologias Utilizadas

- Python 3
- Manipulação de arquivos
- Estruturas condicionais
- Estruturas de repetição
- Organização lógica modular

---

## 🚀 Como Executar

1. Certifique-se de ter o Python 3 instalado.
2. Coloque o arquivo `quiz.txt` na mesma pasta do script principal.
3. Execute no terminal:

```bash
python main.py
