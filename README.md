
# **Implementação de um modelo de LLM para uso local**

- Você pode encontrar diversos modelos em:
  -  https://huggingface.co/models
  - https://www.kaggle.com/models/


- Nesta implementação utilizaremos o modelo Gemma-2b Instruct do Google baixado do site da Hugging Face. Você pode encontrar este modelo aqui: [google/gemma-2b-it](https://huggingface.co/google/gemma-2b-it)

- Atente-se para o tempo de download do modelo e à característica stateless do colab, pois aqui os dados importados desaparecem e todos os processos devem ser reiniciados após o fim da sessão.

- Obtenha um token de acesso da Hugging Face através da página https://huggingface.co/settings/tokens, alguns modelos dependem deste token para serem acessados.

- Esta é uma implementação básica de um modelo pré-treinado. Com algumas alterações no código podemos combinar nossos próprios documentos para obter respostas mais específicas. Estas alterações variaamde acordo com a necessidade do projeto e podem ser tratadas em outros notebooks

- Para acessar o notebook original, clique [aqui](https://colab.research.google.com/drive/1c_N3Uk8-tlt9rrsJ55C9dPHe99dwjZou?usp=sharing).


*Criado por: [Diego Cosamores](https://cosamores.com)*

