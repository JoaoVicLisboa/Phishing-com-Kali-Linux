# Phishing-com-Kali-Linux
📌 Introdução

Este projeto tem como objetivo demonstrar, de forma educativa, como funciona um ataque de phishing e como as técnicas de coleta de credenciais podem ser exploradas por atacantes mal-intencionados. A intenção é auxiliar profissionais e entusiastas de cibersegurança a entenderem a mecânica desses ataques para melhor preveni-los e mitigá-los.

**⚠ Aviso Legal: Este projeto deve ser utilizado apenas em ambientes de teste controlados e com permissão explícita. O uso indevido dessas técnicas para fins maliciosos é ilegal e antiético.**

🎯 Objetivo

O principal objetivo deste projeto é demonstrar como um atacante poderia criar um site falso para capturar credenciais de usuários. No entanto, o foco é instruir sobre:

Como ataques de phishing são realizados.

Como identificar e prevenir tentativas de phishing.

Métodos de detecção e defesa contra phishing.

🔧 Ferramentas Utilizadas

Kali Linux - Distribuição voltada para testes de penetração.

Social-Engineer Toolkit (SET) - Ferramenta para simulação de ataques de engenharia social.

🚀 Configurando o Ambiente

1️⃣ Acesso ao Kali Linux

Certifique-se de que possui acesso às permissões necessárias:

sudo su

2️⃣ Iniciar o Social-Engineer Toolkit (SET)

setoolkit

3️⃣ Selecionar Tipo de Ataque

Escolha a opção Social-engineering attacks.

![image](https://github.com/user-attachments/assets/a6de4aa3-1070-4f06-9084-0a97d77b6d83)

Logo após selecione Web attack vectors.

![image](https://github.com/user-attachments/assets/f4e40fbe-baab-420d-83d6-7661fb2b7c5d)


4️⃣ Definir Método de Ataque

Escolha Credential Harvester Attack Method e depois Site Cloner.
![image](https://github.com/user-attachments/assets/623178d4-d2db-4d51-965a-4bdc772608c0)

![image](https://github.com/user-attachments/assets/fc3fde94-d600-4c75-9a0c-8645e8972f8f)


5️⃣ Configurar o Servidor Local

Descubra seu endereço IP local:
ifconfig
Ou use o Ip que foi apresentado.

Insira o IP da máquina e a URL que deseja clonar (exemplo: Facebook, Gmail, etc.).

6️⃣ Iniciar a Captura

O SET irá criar uma página falsa e armazenar credenciais inseridas em um arquivo de log.

🔐 Como se Defender Contra Phishing

Educação e Conscientização: Treinar usuários para identificar e-mails e sites suspeitos.

Autenticação Multifator (MFA): Impedir que credenciais roubadas sejam suficientes para o acesso.

Ferramentas Anti-Phishing: Utilizar extensões de navegador e soluções de segurança para bloquear ataques.

Monitoramento de Logs: Configurar sistemas de detecção para alertar sobre atividades suspeitas.
