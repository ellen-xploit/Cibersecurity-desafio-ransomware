# Desafio Ransomware

Este repositório é um fork do projeto original [Desafio Ransomware](https://github.com/cassiano-dio/cibersecurity-desafio-ransomware), adaptado por [Ellen](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware) como parte de um desafio do curso de cibersegurança.

O objetivo é demonstrar como criptografar e descriptografar um arquivo de texto usando Python, simulando o funcionamento de um ransomware.

---

## 📚 Conteúdo

1. [Modificações Realizadas](#-modificações-realizadas)
2. [Estrutura do Projeto](#-estrutura-do-projeto)
3. [Como Executar](#-como-executar)
4. [Capturas de Tela](#-capturas-de-tela)
5. [Conceitos Aprendidos](#-conceitos-aprendidos)
6. [Uso e Contribuição](#-uso-e-contribuição)
7. [Aviso Legal](#-aviso-legal)

---

## 🚀 Modificações Realizadas


Neste fork, as seguintes alterações foram implementadas:

<<<<<<< HEAD
- **Arquivo de Texto Único**: `mensagem_secreta.txt` armazena a mensagem original
=======
- **Arquivo de Texto Único**: [`mensagem_secreta.txt`](mensagem_secreta.txt) armazena a mensagem original.
>>>>>>> 939dc39 (Update README.md)
- **Criptografia e Descriptografia**:
  - [`encrypter.py`](encrypter.py): Criptografa o arquivo.
  - [`decrypter.py`](decrypter.py): Descriptografa o arquivo.
- **Capturas de Tela**: Incluídas para documentar o processo.
- **Uso do `venv`**: Ambiente virtual Python para isolar dependências.


---

## 📂 Estrutura do Projeto

- [`mensagem_secreta.txt`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/mensagem_secreta.txt): Arquivo de texto.
- [`encrypter.py`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/encrypter.py): Script de criptografia.
- [`decrypter.py`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/decrypter.py): Script de descriptografia.
- [`README.md`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/README.md): Arquivo principal.
- **Capturas de Tela**:
<<<<<<< HEAD
  - `comandos.png`, `arquivodetexto.png`, `encrypter.png`, `decrypter.png`, 

=======
  - [`comandos.png`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/capturas/comandos.png)
  - [`arquivodetexto.png`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/capturas/arquivodetexto.png)
  - [`encrypter.png`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/capturas/encrypter.png)
  - [`decrypter.png`](https://github.com/ellen-xploit/Cibersecurity-desafio-ransomware/blob/main/capturas/decrypter.png)
>>>>>>> 939dc39 (Update README.md)
---

## 🛠️ Como Executar

1. **Configure o ambiente**:
   - Crie e ative um ambiente virtual:
     ```bash
     python3 -m venv venv
     source venv/bin/activate  # Linux/Mac
     venv\Scripts\activate     # Windows
     ```
   - Instale as dependências:
     ```bash
     pip install cryptography
     ```

2. **Execute os scripts**:
   - Criptografar:
     ```bash
     python encrypter.py
     ```
   - Descriptografar:
     ```bash
     python decrypter.py
     ```
     

---

## 📸 Capturas de Tela

- **Comandos**: ![Comandos](capturas/comandos.png)
- **Arquivo Original**: ![Arquivo Original](capturas/arquivodetexto.png)
- **Código do Encrypter**: ![Código do Encrypter](capturas/encrypter.png)
- **Código do Decrypter**: ![Código do Decrypter](capturas/decrypter.png)
- **Arquivo Criptografado**: ![Arquivo Criptografado](capturas/arquivocriptogra>



## 📚 Conceitos Aprendidos

- **Criptografia Simétrica**: Uso de chaves para criptografar e descriptografar dados.
- **Segurança de Dados**: Proteção de informações confidenciais.
- **Ambientes Virtuais**: Isolamento de dependências com `venv`.
- **Funcionamento de Ransomware**: Simulação de um ataque real para fins educacionais.

## 🤝 Uso e Contribuição

Este repositório é livre para uso, cópia, modificação e compartilhamento, desde que seja para fins de aprendizado e estudo.

### 🚫 Restrições
- **Não use este projeto para atividades maliciosas ou ilegais**.
- Respeite a finalidade educacional do projeto.

### 🙌 Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature

---
## ⚠️ Aviso Legal

Este projeto foi desenvolvido **exclusivamente para fins educacionais** e de aprendizado. Ele simula o funcionamento de um ransomware, mas **não deve ser usado de forma maliciosa ou ilegal**. O objetivo é entender como a criptografia funciona e como os ataques de ransomware podem ser realizados, a fim de desenvolver estratégias de prevenção e proteção.

---

Feito com ❤️  por [Ellen](https://github.com/ellen-xploit)  
Baseado no projeto de [Cassiano Dio](https://github.com/cassiano-dio/cibersecurity-desafio-ransomware) 

