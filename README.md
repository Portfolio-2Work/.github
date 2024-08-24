# Capa

- **Título do Projeto**: 2Work.
- **Nome do Estudante**: Gustavo Henrique Borges.
- **Curso**: Engenharia de Software.
- **Data de Entrega**: 

# Resumo

Breve descrição do conteúdo do documento, incluindo o propósito do projeto e os principais pontos de discussão.

## 1. Introdução

- **Contexto**: Aplicativo para registro de ponto em horário de trabalho, .
- **Justificativa**: Registro de ponto é algo comum em empresas mas muitas ainda necessitam de uma máquina para isso, gerando custo de reposição de tinta, papel e etc...
- **Objetivos**: Permitir que um funcionário posso registrar seu trabalho durante o dia e gerar um painel que o responsável na empresa pelo RH possa ver o rendimento do funcionário.

## 2. Descrição do Projeto

- **Tema do Projeto**: Plataforma chamada 2Work, para registro de trabalho de um funcionário.
- **Problemas a Resolver**: Monitoramente das horas trabalhadas sem a necessidade de comprar uma máquina para isso, de forma totalmente virtual.
- **Limitações**: Não abordará o que foi trabalhado pelo funcionário.

## 3. Especificação Técnica

Descrição detalhada da proposta, incluindo requisitos de software, protocolos, algoritmos, procedimentos, formatos de dados, etc.

### 3.1. Requisitos de Software

## Requisitos Funcionais (RF)

| **Código** | **Descrição** |
|------------|---------------|
| **RF01**   | A API deve permitir a autenticação dos usuários. |
| **RF02**   | A API deve registrar a entrada e saída de pontos de trabalho com data, hora, e localização. |
| **RF03**   | A API deve fornecer um endpoint para consultar os registros de ponto de um empregado específico. |
| **RF04**   | A API deve permitir a consulta de registros de ponto por período. |
| **RF05**   | A API deve permitir a gestão de usuários, como criação, edição e exclusão. |
| **RF06**   | A API deve permitir a exportação dos registros de ponto.|
| **RF07**   | O aplicativo móvel deve permitir que os usuários façam login com suas credenciais. |
| **RF08**   | O aplicativo móvel deve permitir que os usuários registrem o ponto de entrada e saída. |
| **RF09**   | O aplicativo móvel deve mostrar o histórico de pontos registrados pelo usuário. |
| **RF10**   | O aplicativo móvel deve permitir a geolocalização para validar a localização do ponto registrado. |
| **RF11**   | O aplicativo móvel deve ter uma opção para recuperação de senha. |
| **RF12**   | O painel deve permitir que os administradores visualizem os registros de ponto de todos os empregados. |
| **RF13**   | O painel deve permitir a exportação dos registros de ponto. |
| **RF14**   | O painel deve fornecer gráficos e relatórios sobre a assiduidade dos empregados. |
| **RF15**   | O painel deve permitir a gestão de empregados, incluindo adição, edição e remoção. |

## Requisitos Não-Funcionais (RNF)

| **Código** | **Descrição** |
|------------|---------------|
| **RNF01**  | A API e o aplicativo móvel devem seguir as melhores práticas de segurança, incluindo criptografia de dados em trânsito e em repouso. |
| **RNF02**  | O painel web deve ser responsivo, suportando diferentes resoluções de tela. |
| **RNF03**  | O sistema deve ser escalável para permitir o crescimento do número de usuários e dados. |
| **RNF04**  | Os dados devem ser armazenados em um banco de dados relacional, com backup diário automático. |

### 3.2. Considerações de Design

- Discussão sobre as escolhas de design, incluindo alternativas consideradas e justificativas para as decisões tomadas.
- **Visão Inicial da Arquitetura**: Descrição dos componentes principais e suas interconexões.
- **Padrões de Arquitetura**: Indicação de padrões específicos utilizados (ex.: MVC, Microserviços).
- **Modelos C4**: Detalhamento da arquitetura em níveis: Contexto, Contêineres, Componentes, Código.

### 3.3. Stack Tecnológica

- **Linguagens de Programação**: C#, Javascript/Typescript.
- **Frameworks e Bibliotecas**: ReactJS, React Native, Vite, .Net Core.
- **Ferramentas de Desenvolvimento e Gestão de Projeto**: Trello.

### 3.4. Considerações de Segurança

Limitar o envio de requests por IP no app mobile, evitando alguém com a intenção de derrubar a API de conseguir

## 4. Próximos Passos

Descrição dos passos seguintes após a conclusão do documento, com uma visão geral do cronograma para Portfólio I e II.

## 5. Referências

- [Vite](https://vitejs.dev/)
- [ASP.NET Core](https://learn.microsoft.com/pt-br/aspnet/core/?view=aspnetcore-8.0)
- [React Native](https://reactnative.dev/)

## 6. Apêndices (Opcionais)


## 7. Avaliações de Professores

Adicionar três páginas no final do RFC para que os Professores escolhidos possam fazer suas considerações e assinatura:
- Considerações Professor/a:
- Considerações Professor/a:
- Considerações Professor/a:
