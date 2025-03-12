<div align=center>
<img src="https://github.com/user-attachments/assets/305524fa-b731-4f5b-9ec6-8de46b75a1eb" width="200px;" /><br>
</div>
    
## 🤖🧠🐾 Chatbot de Saúde Mental através de Pets com IA e AWS

<p align="center"><i>Um chatbot que auxilia no tratamento mental com auxilio de pets.</i></p>

## 📖 Índice

1.  Monitoramento de Saúde Mental
2.  Integração com Pet Shop
3.  Conteúdo Educativo
4.  Gamificação
5.  Comunidade e Apoio
6.  Benefícios
7.  Contribuidores

##  Objetivo

Criar um sistema que auxilie estudantes a monitorarem sua saúde mental enquanto utilizam interações com pets como uma forma de terapia e alívio do estresse acadêmico.

## Funcionalidades
## 1 - Monitoramento de Saúde Mental:

- Aplicativo ou plataforma web com questionários regulares (baseados em escalas validadas como PHQ-9 ou GAD-7).
- Identificação de padrões de humor, níveis de estresse e qualidade do sono.
- Envio de alertas caso os níveis indiquem necessidade de ajuda profissional.

## 2 - Integração com Pet Shop:

- Pet-friendly break: Sistema para agendar visitas a um pet shop parceiro onde os estudantes podem interagir com animais.
- Adote ou passeie: Funcionalidade para agendar passeios com pets ou até mesmo participar de programas de adoção responsável.

## 3 - Conteúdo Educativo:

- Vídeos e artigos sobre como animais ajudam na saúde mental.
- Técnicas de mindfulness com pets.

## 4 - Gamificação:

- Recompensas por manter hábitos saudáveis, como cupons de desconto no pet shop.
- Pontuação por check-ins em interações com os pets.

## 5 - Comunidade e Apoio:

- Fórum para estudantes compartilharem experiências.
- Área para depoimentos sobre os benefícios emocionais de interagir com animais.

## 6 - Benefícios

- Melhora na saúde mental e emocional dos estudantes.
- Incentivo a adotar e cuidar de animais.
- Parcerias com pet shops que podem oferecer terapias assistidas por animais e aumentar sua clientela.

## Tecnologias Utilizadas

### 1. Route 53

Serviço de DNS da AWS que roteia as solicitações do usuário para os serviços adequados.

### 2. Amazon Lex

Serviço de chatbot da AWS que interpreta a entrada do usuário e responde com base em regras definidas.

### 3. Amazon Bredrock

Serviço de IA generativa que pode processar a entrada e gerar respostas mais complexas, integrando modelos avançados.

### 4. Amazon Comprehend

Serviço de processamento de linguagem natural que analisa a intenção e o sentimento do texto fornecido pelo usuário.

### 5. Código Python

Um componente customizado que executa lógica adicional, possivelmente orquestrando as respostas geradas.

### 6. AWS Lambda

Serviço serverless que executa funções sob demanda, possivelmente processando dados e interagindo com o banco de dados.

### 7. Amazon DynamoDB

Banco de dados NoSQL que armazena informações, como histórico de interações ou dados relevantes para o processamento.

![Fluxo](https://github.com/user-attachments/assets/d43dec30-3e2e-4beb-9a33-821049d2f28a)


## Execução de Utilização

### Fluxo de Funcionamento
1. O usuário envia uma requisição via Route 53.
2. O Amazon Lex interpreta a intenção da mensagem.
3. O Amazon Bedrock pode ser usado para gerar respostas com IA.
4. O Amazon Comprehend pode analisar a entrada para extrair informações, como sentimentos e entidades.
5. Um código em Python pode orquestrar a lógica e acionar outras funções.
6. A AWS Lambda processa os dados e interage com o DynamoDB para armazenar ou recuperar informações.
7. A resposta processada retorna para o usuário.

## Próximos Passos:

- [ ] Validação da ideia: Pesquisar interesse em universidades e pet shops locais.
- [ ] Parcerias: Fechar acordo com pet shops que tenham estrutura para visitas.
- [ ] Prototipagem: Desenvolver o MVP do aplicativo para testes iniciais.

## 7 - 👥 Colaboradores

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/claudio-reinaldo" title="GitHub">
        <img src="https://github.com/user-attachments/assets/08face70-eea6-4c66-a234-99ed13c5fef4" width="100px;" alt="Foto Claudio"/><br>
        <sub>
          <b><a href="https://www.linkedin.com/in/claudioreinaldo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
         <sub>           
  
  <b>Claudio Reinaldo</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/EliasOliveira1" title="GitHub">
        <img src="https://github.com/user-attachments/assets/7c050c9f-a73a-4ffe-8867-fd48afb5ff11" width="100px;" alt="Foto Elias"/><br>
        <sub>
          <b><a href="https://github.com/EliasOliveira1" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank">
          <sub>
          
  <b>Elias Oliveira</b>
        </sub>
      </a>
    </td>    
    <td align="center">
      <a href="https://www.linkedin.com/in/leonardo-silva-19b349338/" title="GitHub">
        <img src="https://github.com/user-attachments/assets/e6dcc6dc-54ea-4fd2-92db-e8af363300f3" width="100px;" alt="Foto Leo"/><br>
        <sub>
          <b><a href="https://www.linkedin.com/in/leonardo-silva-19b349338/" target="_blank">
        <sub>
          <b><a href="https://www.linkedin.com/in/leonardo-silva-19b349338/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank">
          <sub>
          
  <b>Leonardo Silva</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
