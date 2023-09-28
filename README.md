<img src="https://github.com/duartebianca/flAshI/blob/main/img/flashi_logo_preto.png" alt="logo" width="100" />

# flAshI - Gerador de Flashcards para Aprendizado de Idiomas 📚🌎
Boas-vindas à documentação do flAshI! Aqui você encontrará informações sobre a plataforma, que é uma aplicação voltada para a geração de decks de flashcards projetados para o aprendizado de idiomas. Os flashcards incluem imagens geradas pelo DALL-E, áudio de pronúncia gerado pelo Text to Speech, frases idiomáticas no idioma original e suas respectivas traduções feitas pelo GPT 3.5-turbo.

## Grupo do Projeto
- Camila Xavier (cxm)
- Breno Cavalcanti (bmmuc)
- Felipe Souza (frs3)
- Bianca Duarte (bds)
- Luísa Mendes (mlmsp)
- Maike Menezes (mhrm2)
- Roseane Oliveira (rocg)


## Sobre o Projeto 🚀

Aprender um novo idioma pode ser desafiador, e os flashcards são uma ferramenta eficaz amplamente reconhecida para auxiliar nesse processo. O flAshI torna o aprendizado de idiomas mais interativo e divertido, fornecendo uma maneira fácil de criar, compartilhar e estudar flashcards com recursos avançados de IA. Além disso, a exportação para o [Anki](https://ankiweb.net/about) permite utilizar recursos de personalização e repetição espaçada, sendo o último essencial na aprendizagem com idiomas.

### Por que Flashcards para Idiomas? 📖🌟

- **Aprendizado Ativo:** Os flashcards incentivam o aprendizado ativo, onde estudantes são ativamente envolvidos na criação, revisão e teste do seu conhecimento.
- **Memorização Eficaz:** A repetição espaçada é uma técnica comprovada para melhorar a retenção a longo prazo, e os flashcards são ideais para aplicá-la.
- **Personalização:** Com o flAshI, os estudantes podem criar seus próprios flashcards com palavras e frases específicas que desejam aprender.
- **Recursos Multimídia:** A inclusão de áudio de pronúncia e imagens geradas pelo DALL-E torna o aprendizado de idiomas mais rico e envolvente.

### Como Utilizar o flAshI 🔍📝

Para utilizar o flAshI e gerar seus próprios flashcards, siga as etapas abaixo:

1. Acesse o [flAshI](https://flashi-pwa.netlify.app/). Por favor, esteja ciente de que, devido ao processo de renderização, a aplicação deve demorar para carregar pela primeira vez, se você não fez nenhuma requisição por um tempo.
2. Certifique-se de ter as chaves de API necessárias:
   - 2.1 [Chave da OpenAI API](https://platform.openai.com/docs/api-reference/turbo): Esta chave é necessária para geração de frases e imagens e tradução de texto.<br> **```⚠️ O uso do flAshI consome créditos e, consequentemente, dinheiro ⚠️ ```**
     - Como obter?
        - Vá em [API Keys](https://platform.openai.com/account/api-keys).
        - Selecione "create a new secret key".
        - Certifique-se de ir em Biling e ativar uma forma de pagamento.
   - 2.2 [Chave da API do Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech): Esta chave é usada para a síntese de fala.<br> **```⚠️ O uso do flAshI consome créditos e, consequentemente, dinheiro ⚠️ ```**
     - Como obter?
       - Passo 1: Configurar uma Conta do Google Cloud Platform (GCP)
         Se você ainda não tiver uma conta do GCP, siga estas etapas:
         1. Acesse https://cloud.google.com/.
         2. Clique em "Get started for free" (Comece gratuitamente) ou "Console" no canto superior direito.
         3. Siga as instruções para criar uma nova conta ou fazer login em uma conta existente
       - Passo 2: Criar um Projeto no GCP
         Após fazer login na sua conta do GCP, siga estas etapas para criar um projeto:
         1. No Console do GCP, clique no menu de navegação (ícone de três linhas no canto superior esquerdo) e selecione "Cloud Console".
         2. Clique no seletor de projetos no topo da página e clique em "Novo projeto".
         3. Preencha o nome do projeto, selecione uma organização (se aplicável) e escolha um local (região) para o projeto.
         4. Clique em "Criar" para criar o projeto.
       - Passo 3: Habilitar a API do Text-to-Speech
         1. No Console do GCP, clique no menu de navegação e vá para "APIs & Services" (APIs e Serviços) > "Dashboard".
         2. Clique no botão "+ ENABLE APIS AND SERVICES" (Habilitar APIs e Serviços).
         3. Clique em "Enable" (Habilitar) para ativar a API para o seu projeto.
        - Passo 4: Criar uma Chave de API
         1. No Console do GCP, clique no menu de navegação e vá para "APIs & Services" (APIs e Serviços) > "Credentials" (Credenciais).
         2. Na guia "Credentials" (Credenciais), clique no botão "+ CREATE CREDENTIALS" (Criar Credenciais) e selecione "API Key".
         3. Configure a chave em "Edit API key", conforme Passo 5.
        - Passo 5: Configure a Chave de API
          Agora você possui uma chave de API do Google Cloud Text-to-Speech e pode usá-la para integrar a funcionalidade de conversão de texto em fala em seus aplicativos ou serviços. Certifique-se de seguir as práticas recomendadas de segurança ao usar chaves de API. Lembre-se de manter a chave em um local seguro e não compartilhá-la publicamente, pois ela concede acesso ao seu projeto no GCP.    
4. Siga as instruções que aparecerão na tela. Você será solicitado a inserir uma ou mais palavras separadas por vírgula que deseja incluir nos seus flashcards.

5. Aguarde um momento enquanto o flAshI gera os flashcards para você. Você pode observar nossa animação fofa durante este processo :)

6. Exportação para o Anki: Se você deseja exportar os flashcards para o Anki, esteja ciente de que esse processo pode demorar um pouco, dependendo da quantidade de flashcards gerados.

7. Desempenho do Aplicativo: O flAshI tende a ter um melhor desempenho em notebooks e PCs do que em dispositivos móveis, devido à complexidade das operações de IA e renderização de imagens.

Aproveite a jornada de aprendizado de idiomas com o flAshI e bons estudos! 🌟📖🗣️

## Tecnologias Utilizadas 🛠️

O flAshI utiliza uma série de tecnologias e modelos de IA para fornecer recursos avançados de aprendizado de idiomas:

- Front-end: [Next.js](https://nextjs.org/), [SASS](https://sass-lang.com/), [Styled-components](https://styled-components.com/), [TypeScript](https://www.typescriptlang.org/), [Redux](https://redux.js.org/)
- Back-end: [TypeORM](https://typeorm.io/), [PostgreSQL](https://www.postgresql.org/)
- Exportação para o Anki: [Flask](https://flask.palletsprojects.com/en/2.1.x/), [GenAnki](https://github.com/kerrickstaley/genanki), [Python](https://www.python.org/).
- IA para Geração de Imagens: [OpenAI API (DALL-E 2)](https://platform.openai.com/docs/api-reference/dall-e)
- IA para Tradução de Texto: [OpenAI API (GPT-3.5 Turbo)](https://platform.openai.com/docs/api-reference/turbo)
- IA para Síntese de Fala: [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech)

## Códigos de Experimentações, intermediários em Python ou ferramentas simples:
- [Exportação para o Anki em Python](https://colab.research.google.com/drive/1bz85zxuMX0oJtk0DePmC4BdcsU5dTwXq?usp=sharing): Exportação original usando o Genanki em Python, sem conexão com TS.
- [Plan and Execute | LangChain em Python](https://colab.research.google.com/drive/1iUcNyd8I78xLaGN2BFKAa18mA-L3zR8j?usp=sharing): Experimentação com agente Plan and Execute do LangChain, que não foi utilizado devido a previsibilidade do agente. O motivo da tentativa foi utilizar a ferramenta de pesquisa para obter mais contexto na criação de frases e, quem sabe, evoluir a ferramenta.
- [Geração de Voz com Text to Speech em Python](https://colab.research.google.com/drive/1la1k9SwkStlbPlM-Eu_uvbXOvoZaQfLm?usp=sharing): Geração de arquivos .ogg utilizando Google Cloud TTS. 
- [Processamento de Dados para gerar decks padrões](https://colab.research.google.com/drive/1CspUnJgFCrpKCJVVe7pc1CD4KEAsTUx8?usp=sharing): Extrai palavras de PDF do Cambridge English para gerar decks padrões (não implementados porque o back-end não foi).
- Códigos disponíveis também [aqui](https://github.com/duartebianca/flAshI/tree/main/experimentacoes-intermediarios-etc).

## Como Contribuir 🤝🌐

Se você deseja ajudar no desenvolvimento desta ferramenta, siga as etapas abaixo:

1. Escolha o repositório que deseja contribuir:
   - [flashi-app-front](https://github.com/maikermenezes/flashi-app-front): Front-end da aplicação web.
   - [anki-export](https://github.com/rosean3/anki-export): Exportação de decks para o formato Anki, utilizando Python, Flask e Next.
   - [flashi-app-back](https://github.com/maikermenezes/flashi-app-back): Back-end da aplicação (recursos em desenvolvimento ou com deploy pendente).
   - **A documentação de cada repositório está [aqui](https://github.com/duartebianca/flAshI/tree/main/outros-readme)**.
2. Faça um fork do repositório no GitHub.
3. Clone o repositório forked em sua máquina local.
4. Explore as atividades a serem feitas e as já concluídas no repositório [flashi-app-back](https://github.com/maikermenezes/flashi-app-back) para saber onde você pode contribuir.
5. Faça as modificações necessárias e crie um branch para suas alterações.
6. Faça push de suas alterações para o fork no GitHub.
7. Após concluir suas alterações, faça um pull request para o repositório original, descrevendo suas alterações e o problema que elas resolvem.
8. Nossa equipe revisará suas contribuições e as incorporará ao projeto.

## Status do Repositório flashi-app-back 📊

O back-end não foi deployado na aplicação até a data da apresentação do projeto. Destacamos aqui as atividades a serem feitas e as já concluídas no repositório [flashi-app-back](https://github.com/maikermenezes/flashi-app-back):
- Atividades já concluídas:
  - Login, no geral, funcionava locamente ✅
  - Criação do banco de dados ✅
  - Salvamento dos decks no banco de dados ✅
- Atividades a serem feitas:
  - Login não funciona no deploy (apresentou inconsistências) ❌

Se você estiver interessado em contribuir para essas tarefas ou desejar adicionar novos recursos ao flAshI, fique à vontade para colaborar!

### Agradecemos por sua contribuição para o projeto flAshI! ✨🌟

Se você tiver alguma dúvida ou precisar de assistência, sinta-se à vontade para abrir uma issue ou entrar em contato com nossa equipe de desenvolvimento. Juntos, podemos tornar o aprendizado de idiomas mais acessível e eficaz para todos! 🌎📖🗣️
