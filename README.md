Chat Serverless com IA Generativa na AWS

📚 Visão Geral
Este projeto demonstra a construção de um sistema de chat inteligente e escalável, utilizando uma arquitetura 100% serverless na AWS. A solução integra o poder do Amazon Bedrock para acesso a modelos de Inteligência Artificial Generativa de ponta, orquestrado por uma função AWS Lambda e exposto de forma segura através do API Gateway. A interface do usuário é hospedada de forma custo-efetiva em um bucket S3.

O resultado é uma aplicação web responsiva, capaz de manter conversas complexas, gerar código, traduzir idiomas e muito mais, servindo como um case prático de Cloud Computing e Segurança de Aplicações de IA.

🏗️ Arquitetura do Sistema
A arquitetura foi projetada para ser eficiente, escalável e de baixa manutenção, seguindo o fluxo abaixo:

[Usuário] → [S3 (Site Estático)] → [API Gateway] → [AWS Lambda] → [Amazon Bedrock (Claude 3 Haiku)]

✨ Principais Funcionalidades do Projeto
Interface Web Reativa: Front-end simples e intuitivo hospedado no S3, garantindo alta disponibilidade e baixo custo.

Computação Serverless: O back-end utiliza AWS Lambda, eliminando a necessidade de gerenciar servidores e escalando automaticamente com a demanda.

API Segura e Escalável: O API Gateway atua como um ponto de entrada seguro para as requisições, gerenciando o tráfego e a autorização.

Inteligência Artificial de Ponta: Integração direta com o Amazon Bedrock para explorar as capacidades avançadas do modelo Claude 3 Haiku.

🧠 IA Generativa: Poder e Versatilidade com Claude 3 Haiku
O coração deste projeto é o modelo Claude 3 Haiku da Anthropic, acessado via Amazon Bedrock. Este modelo foi escolhido por sua combinação de velocidade, precisão e um vasto leque de funcionalidades, que incluem:

Raciocínio e Análise Complexos: Capacidade de interpretar e resolver problemas de múltiplos passos.

Geração e Otimização de Código: Escreve, depura e explica código em diversas linguagens de programação.

Capacidades de Conversação: Mantém diálogos fluidos e contextuais, otimizado para aplicações de chat.

Suporte Multilíngue e Tradução: Processa e traduz textos em vários idiomas com alta fidelidade.

Resumo e Geração de Texto: Cria resumos concisos de documentos longos e gera novos textos a partir de um prompt.

Question Answering (Q&A): Responde a perguntas de forma precisa, atuando como uma base de conhecimento interativa.

Pronto para RAG (Retrieval-Augmented Generation): Arquitetado para ser facilmente integrado a bases de dados externas, enriquecendo suas respostas com informações específicas.

Atuação como Agente: Capacidade de executar tarefas sequenciais e tomar decisões para alcançar um objetivo.

🛠️ Tecnologias Utilizadas
AWS Bedrock: Acesso gerenciado a modelos de IA Generativa.

AWS Lambda: Execução de código serverless.

AWS S3: Hospedagem de site estático.

AWS API Gateway: Criação e gerenciamento de APIs REST.

Python 3.12: Linguagem do back-end (função Lambda).

HTML/JavaScript: Estrutura do front-end.

---

<!-- Início da seção "Contato" -->
<h2>🌐 Contate-me: </h2>
<div>
  <p>Developed by <b>Fábio Nogueira</b></p>
</div>
<p>
<a href="https://www.linkedin.com/in/faanogueira/" target="_blank"><img style="padding-right: 10px;" src="https://img.icons8.com/?size=100&id=13930&format=png&color=000000" target="_blank" width="80"></a>
<a href="https://github.com/faanogueira" target="_blank"><img style="padding-right: 10px;" src="https://img.icons8.com/?size=100&id=AZOZNnY73haj&format=png&color=000000" target="_blank" width="80"></a>
<a href="https://api.whatsapp.com/send?phone=5571983937557" target="_blank"><img style="padding-right: 10px;" src="https://img.icons8.com/?size=100&id=16713&format=png&color=000000" target="_blank" width="80"></a>
<a href="mailto:faanogueira@gmail.com"><img style="padding-right: 10px;" src="https://img.icons8.com/?size=100&id=P7UIlhbpWzZm&format=png&color=000000" target="_blank" width="80"></a> 
</p>
<!-- Fim da seção "Contato" -->
