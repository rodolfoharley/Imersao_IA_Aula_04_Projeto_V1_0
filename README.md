# Imersao_IA_Aula_04_Projeto_V1_0
Projeto Treino de Inglês para Imersao IA Alura + Google

Descrição:
Este código Python demonstra como criar um aplicativo para aprender inglês usando o Google Generative AI. O aplicativo gera frases em inglês e solicita ao usuário que as traduza para o português ou Inglês. O aplicativo fornece feedback e acompanha o progresso do usuário ao longo de várias rodadas.

Funcionalidades:
Gera frases em inglês com até 25 palavras.
Traduz frases do inglês para o português (funcionalidade a ser implementada).
Fornece feedback imediato ao usuário.
Acompanha o progresso do usuário ao longo de várias rodadas.
Gera um relatório ao final mostrando a evolução do percentual de acertos do usuário. 
Gera um gráfico de linha mostrando a evolução do percentual de acertos do usuário. (funcionalidade a ser implementada).

Requisitos:
Conta do Google.
API Key do Google Generative AI.
Python 3.6 ou superior.
Bibliotecas:
google-generativeai
IPython (opcional)
matplotlib (opcional para gerar gráficos)
nltk (opcional para geração de frases mais complexas)
spacy (opcional para geração de frases mais complexas)
goslate (opcional para tradução)
textblob (opcional para tradução)

Instalação:
Instale a biblioteca google-generativeai:
Bash
pip install -U -q google-generativeai
Use o código com cuidado.
content_copy

Uso:
Crie um arquivo Python e copie o código fonte fornecido.
Substitua YOUR_API_KEY pela sua API Key do Google Generative AI no código.
Execute o código no Python.
Digite "Olá" para iniciar o aplicativo.
Siga as instruções na tela para traduzir frases em inglês e acompanhar seu progresso.
Digite "fim" para finalizar o aplicativo.

Observações:
Este código é uma estrutura básica e precisa ser complementado com a lógica de geração de frases, tradução e apresentação do gráfico.
Você pode usar bibliotecas como nltk, spacy, goslate ou textblob para auxiliar na geração de frases, tradução e processamento de linguagem natural.
É importante ter um conjunto de frases em inglês e suas respectivas traduções para o português.
A biblioteca matplotlib é usada para gerar o gráfico.

Exemplo de uso:
Traduza: The cat is on the table.
Sua resposta: O gato está em cima da mesa
Correto!

...

Você acertou 70% das perguntas!
Deseja continuar? (s/n): n

# Gráfico mostrando a evolução dos acertos em cada rodada
Recursos Adicionais:

Documentação do Google Generative AI: https://cloud.google.com/ai/generative-ai
Exemplos de código do Google Generative AI: https://cloud.google.com/ai/generative-ai
Tutoriais do Google Generative AI: https://www.youtube.com/watch?v=tmHXGbro8NY
