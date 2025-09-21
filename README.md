📌 DIO - Trilha .NET - Programação Orientada a Objetos

Este repositório contém a solução para o desafio de projeto do módulo Programação Orientada a Objetos (POO) da DIO (Digital Innovation One)
.

🚀 Desafio de Projeto

O objetivo foi desenvolver um sistema de celulares em C#, aplicando conceitos de abstração, herança e polimorfismo.

O programa foi construído como uma aplicação console em .NET, seguindo o diagrama de classes fornecido no desafio.

📖 Contexto

O sistema simula o comportamento de diferentes modelos de celulares (Nokia e iPhone), permitindo reuso de código e diferenciação de comportamento através da orientação a objetos.

📌 Regras e Validações

📱 A classe Smartphone deve ser abstrata, servindo apenas como modelo.

📱 As classes Nokia e iPhone devem herdar de Smartphone.

📱 O método InstalarAplicativo deve ser sobrescrito nas classes filhas, simulando o comportamento específico de cada marca.

🗂️ Estrutura do Projeto

Smartphone.cs → Classe abstrata base para os celulares.

Nokia.cs → Classe filha que implementa comportamento do Nokia.

iPhone.cs → Classe filha que implementa comportamento do iPhone.

Program.cs → Classe principal para execução e testes no console.

🖥️ Exemplo de Uso
Smartphone nokia = new Nokia(numero: "123456", modelo: "Nokia Tijolão", imei: "111111", memoria: 64);
nokia.Ligar();
nokia.InstalarAplicativo("WhatsApp");

Smartphone iphone = new Iphone(numero: "987654", modelo: "iPhone 14", imei: "222222", memoria: 128);
iphone.ReceberLigacao();
iphone.InstalarAplicativo("Telegram");

📚 Aprendizados

Criação de classes abstratas em C#.

Implementação de herança e polimorfismo.

Diferença entre métodos virtuais e sobrescritos.

Estruturação de um projeto console em .NET.

✍️ Desenvolvido como parte da Trilha .NET - DIO
