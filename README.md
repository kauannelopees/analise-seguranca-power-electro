# analise-seguranca-power-electro

🔐 Análise de Segurança – Sistema Power Electro

📌 Descrição
Este projeto apresenta uma análise básica de segurança em um sistema web desenvolvido com HTML e CSS, com foco na identificação de vulnerabilidades iniciais.

🖥️ Tela de Login

<img src="https://github.com/user-attachments/assets/9b08b1c4-2ae6-4e40-a07a-5e7743c20d2e" width="500">

🔍 Análise
A tela de login possui campos de e-mail e senha, porém não há validação de dados implementada.

⚠️ Problema
O sistema não realiza autenticação real, permitindo a inserção de qualquer informação.

💡 Melhoria
Implementar validação de dados com JavaScript e autenticação com backend.

🖥️ Tela de Convite

<img src="https://github.com/user-attachments/assets/abaea287-ba29-4062-8ce0-e1b8a17f8702" width="500">

🔍 Análise
A página apresenta informações estáticas que podem ser alteradas pelo usuário utilizando ferramentas do navegador.

⚠️ Problema
Os dados podem ser manipulados diretamente no frontend.

💡 Melhoria
Utilizar backend para proteger e validar as informações exibidas.

🧠 Conclusão
Por ser uma aplicação apenas em HTML e CSS, o sistema não possui mecanismos de segurança, sendo vulnerável à manipulação e ausência de validação de dados.
