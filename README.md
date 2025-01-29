# Desafio Ransomware | Santander Bootcamp Cibersecurity

## Ferramentas  e tecnologias utilizadas no decorrer do laboratório:
* **Oracle Virtual box**
* **Kali Linux**
* **Python**
* **Biblioteca pyaes**
## Objetivo do desafio
Este projeto teve como objetivo desenvolver dois scripts em Python para simular um ataque ransomware em um ambiente controlado.
* **O primeiro script, ```encrypter.py```, é responsável por criptografar o conteúdo do arquivo ```teste.txt```, alterando seu nome para ```teste.txt.ransomwaretroll```.**
* **O segundo script, ```decrypter.py```, executa a função inversa, descriptografando o conteúdo do arquivo ```teste.txt.ransomwaretroll``` e restaurando seu nome original para ```teste.txt```.**
* **OBS: O código fonte dos dois scripts se encontram nesse repositório .** <img align="center" alt="joao-Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" />
## Executando o script
Para criptografar, no Kali Linux, utilize:
``` bash
python3 encrypter.py
```
Para descriptografar, no Kali Linux, utilize:
``` bash
python3 decrypter.py
```
