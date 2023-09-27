<img src="https://github.com/duartebianca/flAshI/blob/main/img/flashi_logo_preto.png" alt="logo" width="100" />

# flAshI - Gerador de Flashcards para Aprendizado de Idiomas 📚🌎
Boas-vindas à documentação do flAshI! Aqui você encontrará informações sobre a plataforma, que é uma aplicação voltada para a geração de decks de flashcards projetados para o aprendizado de idiomas. Os flashcards incluem imagens geradas pelo DALL-E, áudio de pronúncia gerado pelo Text to Speech, frases idiomáticas no idioma original e suas respectivas traduções feitas pelo GPT 3.5-turbo.

## Sobre o Projeto 🚀

Aprender um novo idioma pode ser desafiador, e os flashcards são uma ferramenta eficaz amplamente reconhecida para auxiliar nesse processo. O flAshI torna o aprendizado de idiomas mais interativo e divertido, fornecendo uma maneira fácil de criar, compartilhar e estudar flashcards com recursos avançados de IA. Além disso, a exportação para o [Anki](https://ankiweb.net/about) permite utilizar recursos de personalização e repetição espaçada, sendo o último essencial na aprendizagem com idiomas.

### Por que Flashcards para Idiomas? 📖🌟

- **Aprendizado Ativo:** Os flashcards incentivam o aprendizado ativo, onde estudantes são ativamente envolvidos na criação, revisão e teste do seu conhecimento.
- **Memorização Eficaz:** A repetição espaçada é uma técnica comprovada para melhorar a retenção a longo prazo, e os flashcards são ideais para aplicá-la.
- **Personalização:** Com o flAshI, os estudantes podem criar seus próprios flashcards com palavras e frases específicas que desejam aprender.
- **Recursos Multimídia:** A inclusão de áudio de pronúncia e imagens geradas pelo DALL-E torna o aprendizado de idiomas mais rico e envolvente.

# flAshI - Plataforma de Flashcards para Aprendizado de Idiomas 📚🌎

Bem-vindo ao repositório principal do projeto flAshI! Aqui você encontrará informações sobre a plataforma flAshI, que é uma aplicação voltada para a geração de decks de flashcards projetados para o aprendizado de idiomas. Os flashcards incluem imagens geradas pelo modelo DALL-E, áudio de pronúncia, frases idiomáticas no idioma original e suas respectivas traduções.

## Sobre o Projeto 🚀

Aprender um novo idioma pode ser desafiador, e os flashcards são uma ferramenta eficaz amplamente reconhecida para auxiliar nesse processo. Eles se baseiam na ciência da aprendizagem espacial e da repetição espaçada, tornando o flAshI uma ferramenta poderosa para estudantes de idiomas.

### Como Utilizar o flAshI 🔍📝

Para utilizar o flAshI e gerar seus próprios flashcards, siga as etapas abaixo:

1. Acesse o [flAshI](https://flashi-pwa.netlify.app/). Por favor, esteja ciente de que, devido ao processo de renderização, a aplicação deve demorar para carregar pela primeira vez, se você não fez nenhuma requisição por um tempo.
2. Certifique-se de ter as chaves de API necessárias:
   - 2.1 [Chave da OpenAI API](https://platform.openai.com/docs/api-reference/turbo): Esta chave é necessária para geração de frases e imagens e tradução de texto.
     - 2.1.1 
   - 2.2 [Chave da API do Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech): Esta chave é usada para a síntese de fala.
     - 2.2.1 Como obter?
       - .

4. Siga as instruções que aparecerão na tela. Você será solicitado a inserir uma ou mais palavras separadas por vírgula que deseja incluir nos seus flashcards.

5. Aguarde um momento enquanto o flAshI gera os flashcards para você. Você pode observar uma animação durante esse processo.

6. Exportação para o Anki: Se você deseja exportar os flashcards para o Anki, esteja ciente de que esse processo pode demorar um pouco, dependendo da quantidade de flashcards gerados.

7. Desempenho do Aplicativo: O flAshI tende a ter um melhor desempenho em notebooks e PCs do que em dispositivos móveis, devido à complexidade das operações de IA e renderização de imagens.

Aproveite a jornada de aprendizado de idiomas com o flAshI e bons estudos! 🌟📖🗣️

## Como Contribuir 🤝🌐

Se você deseja ajudar no desenvolvimento desta ferramenta, siga as etapas abaixo:

1. Escolha o repositório que deseja contribuir:
   - [flashi-app-front](https://github.com/maikermenezes/flashi-app-front): Front-end da aplicação web.
   - [anki-export](https://github.com/rosean3/anki-export): Exportação de decks para o formato Anki, utilizando Python, Flask e Next.
   - [flashi-app-back](https://github.com/maikermenezes/flashi-app-back): Back-end da aplicação (recursos em desenvolvimento ou com deploy pendente).

2. Clone o repositório escolhido:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

3. Explore as atividades a serem feitas e as já concluídas no repositório [flashi-app-back](https://github.com/maikermenezes/flashi-app-back) para saber onde você pode contribuir.

4. Faça as modificações necessárias e crie um branch para suas alterações:

   ```bash
   git checkout -b minha-contribuicao
   ```

5. Após concluir suas alterações, faça um pull request no repositório correspondente.

6. Nossa equipe revisará suas contribuições e as incorporará ao projeto.

## Tecnologias Utilizadas 🛠️

O flAshI utiliza uma série de tecnologias e modelos de IA para fornecer recursos avançados de aprendizado de idiomas:

- Front-end: [Next.js](https://nextjs.org/), [SASS](https://sass-lang.com/), [Styled-components](https://styled-components.com/), [TypeScript](https://www.typescriptlang.org/), [Redux](https://redux.js.org/)
- Back-end: [Express](https://expressjs.com/), [Flask](https://flask.palletsprojects.com/en/2.1.x/), [TypeORM](https://typeorm.io/), [PostgreSQL](https://www.postgresql.org/)
- IA para Geração de Imagens: [OpenAI API (DALL-E 2)](https://platform.openai.com/docs/api-reference/dall-e)
- IA para Tradução de Texto: [OpenAI API (GPT-3.5 Turbo)](https://platform.openai.com/docs/api-reference/turbo)
- IA para Síntese de Fala: [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech)

## Status do Repositório flashi-app-back 📊

O back-end não foi deployado na aplicação até a data da apresentação do projeto. Destacamos aqui as atividades a serem feitas e as já concluídas no repositório [flashi-app-back](https://github.com/maikermenezes/flashi-app-back):

- Atividades:
  - Login não funciona no deploy (e nem sempre localmente) ❌
  - 

Se você estiver interessado em contribuir para essas tarefas ou desejar adicionar novos recursos ao flAshI, fique à vontade para colaborar!

### Agradecemos por sua contribuição para o projeto flAshI! ✨🌟

Se você tiver alguma dúvida ou precisar de assistência, sinta-se à vontade para abrir uma issue ou entrar em contato com nossa equipe de desenvolvimento. Juntos, podemos tornar o aprendizado de idiomas mais acessível e eficaz para todos! 🌎📖🗣️
