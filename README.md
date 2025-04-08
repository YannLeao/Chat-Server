# Projeto de Chat Cliente-Servidor - Redes de Computadores 🌐💻

## Sobre o Projeto

Este é o **Projeto 1 da disciplina de Redes de Computadores** do curso de Engenharia da Computação na **Universidade Federal Rural de Pernambuco UFRPE**. O objetivo é desenvolver um **Chat Cliente-Servidor** com funcionalidades crescentes em três versões, cada uma explorando conceitos como **conexão TCP**, **threads** e **interface gráfica**.

No projeto foi dado a opção entre **Python** ou **C++**. esse primeiro momento optei por Python.

## Ferramentas utilizadas

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Tkinter-FFCD00?style=for-the-badge&logo=python&logoColor=black" alt="Tkinter">
</div>


> O projeto utiliza programação com threads e sockets para permitir comunicação em tempo real entre clientes.

## Funcionalidades por Versão

### Chat - Versão 1

Nesta primeira versão, o projeto tem como objetivo estabelecer uma **comunicação direta entre cliente e servidor**, onde ambos podem enviar e receber mensagens de forma simultânea. Para isso, utilizamos threads que permitem que cliente e servidor operem de forma independente, garantindo uma comunicação sem bloqueios.

### Chat - Versão 2

A segunda versão do projeto expande o chat para **suportar múltiplos clientes simultâneos**. Para isso, o servidor passa a gerenciar uma nova thread para cada cliente que se conecta, garantindo que todos os clientes possam conversar com o servidor de forma independente.

### Chat - Versão 3

Na versão final, o chat permite que os **clientes conversem diretamente entre si**. O servidor atua como intermediário e roteia as mensagens para o destinatário correto, mantendo uma lista de clientes conectados.

---

## Experiência Adquirida

Este projeto foi uma oportunidade para aprofundar conhecimentos em:
- **Comunicação Cliente-Servidor** e uso de **Sockets**
- **Programação Concorrente** com threads para operações simultâneas
- **Interface Gráfica** com Tkinter para criar uma aplicação de chat interativa
---

## 📚 Referências e Materiais de Estudo

- [Documentação do Python Socket](https://docs.python.org/3/library/socket.html)
- [Tkinter Documentation](https://docs.python.org/3/library/tkinter.html)
- [Threading em Python](https://docs.python.org/3/library/threading.html)
