# Azure-OpenAI-no-PlayGround
## O objetivo deste desafio é utilizar o Playground do Azure OpenAI para gerar conteúdos e compreender as diferentes configurações e parâmetros.
## Para realizar esse desafio, foi criado uma implementação utilizando gpt-35-turbo-16 Uma vez que este é um recurso gratuito, o uso acabou ficando bastante limitado. Nos parâmetros, eu consegui configurar a resposta máxima em apenas 800 tokens. Fiz prints dos testes onde mostrarei o resultado a seguir.
# Testes no PlayGround
### Depois de criado a implementação fiz os primeiros teste com o mesmo texto de prompt que foi usado pelo professor na aula. Observem que nos parametros do chat eu iniciei com Temperatura e Top-p no máximo: 
- Mensagens anteriores incluídas = 10
- Resposta máxima = 800
- Temperatura = 1
- Top-P = 1

![Captura de Tela (115)](https://github.com/user-attachments/assets/0c3d77ad-563a-40d5-8d1f-642d1c803578)

Como podemos ver com os parametros Temperatura e Top-P no máximo, a resposta do chat foi bem criativa.

### No teste seguinte usei o mesmo prompt, mas dessa vez o parametro Temperatura foi zerado e o Top-P continuou no máximo.
- Mensagens anteriores incluídas = 10
- Resposta máxima = 800
- Temperatura = 0
- Top-P = 1

![Captura de Tela (116)](https://github.com/user-attachments/assets/1ec98235-b548-4229-bd9d-c8d22c073572)

Como esperado a resposta foi diferente da primeira.

### O teste seguinte eu fiz o inverso nos parametros, onde Temperatura ficou no máximo e Top-P foi zerado. E no seguinte tanto Temperatura como Top-P foram zerados. Porém a resposta do chat foi a mesma. 

![Captura de Tela (117)](https://github.com/user-attachments/assets/5cc9e526-d567-437c-a170-9ea8369a249b)

![Captura de Tela (118)](https://github.com/user-attachments/assets/336e119b-3d49-4da4-9b7c-9f19bb4b6218)

### Nesse teste decidi colocar os parametros indicados pelo professor, onde Temperatura ficou com o valor de 0.65 e Top-P ficou em 0.3.
- Mensagens anteriores incluídas = 10
- Resposta máxima = 800
- Temperatura = 0.65
- Top-P = 0.3

![Captura de Tela (119)](https://github.com/user-attachments/assets/2c7871b3-ed18-4144-a6db-54e54409c4dc)

Vemos que a resposta foi mais resumidas que as anteriores e bem menos criativa.

### No próximo teste pedi para o chat categorizar uma notícia e continuei com os mesmo parametros do teste anterior. Só alterando as instruções e o contexto do modelo e também adicionando alguns Exemplos, esses foram os resutados:

![Captura de Tela (120)](https://github.com/user-attachments/assets/507a17f5-fb66-4be8-b9f0-31c9fc88a4ef)

![Captura de Tela (121)](https://github.com/user-attachments/assets/b279d982-ef61-4e8e-8a55-42f8f64e951e)

![Captura de Tela (123)](https://github.com/user-attachments/assets/75667ef0-6096-4d6f-bcd3-6be911631f54)

![Captura de Tela (125)](https://github.com/user-attachments/assets/544a5922-92ab-42a9-9c94-4f3094b163c9)

### Por fim criei uma implementação para criar uma imagem, ultilizei o dall-e-3 e pedi para o mesmo criar uma imagem de um aluno estudando programaçõa em um quarto escuro decorado com temas nerds. Esse foi o resultado:

![Captura de Tela (129)](https://github.com/user-attachments/assets/adf47d07-6ecd-4f64-8c5e-7ac530c69cf3)

Achei que faltou um pouco na parte da decoração com temas nerds.

## Por fim, achei ótima a experiência que tive com Azure-OpenAI-no-PlayGround, apesar de ser apenas o começo vou continuar explorando e procurar me aprimorar ainda mais nesse mundo.


