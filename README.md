# Machine-Learning-in-Azure-ML

Nesse tutorial pelo README, irei explicar e demonstrar como você pode utilizar esse recurso chamado Azure ML (Machine Learn) na plataforma de mesmo nome

## Criando o Recurso
1. Indo para a sua conta do Azure, você irá clicar no Create a Resource ou Criar um Recurso
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/8bf85a36-1b9e-4b55-b2bb-3c0bd6b6d74d)
2. Ao clicar nele, você será redirecionado para uma tela com diversas opções de recursos no MarketPlace. Para criar um recurso do Azure ML você irá clicar na Categoria ou Categorie AI + Machine Learning, pesquisar na lupa azul "Azure Machine Learning" e clicar no primeiro recurso com o mesmo nome
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/37e3c218-20e4-4877-af84-45707ebe0c49)
3. Dessa forma, você irá criar o recurso, acrescentando principalmente o nome do grupo de recurso (caso você não tenha é somente criar um novo no Create New ou Criar novo) e colocar o nome do recurso (o resto não é necessário alterar). Quando concluir é só clicar no Review + Create ou Revisar + Criar e depois no Create ou Criar
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/853407e9-2a82-4313-bc52-600ad0084789)


## Configurando o recurso
1. Após a implementação (deployment) for concluída, você irá para a visão inicial do recurso pelo Go To Recurse ou ir para o recurso e clicar no Launch Studio
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/e88ba9b1-5ca7-44ac-bf35-61c2e5e66a96)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/b65c4d8f-4e7c-441e-8bc4-91a09112e260)
2. Ao clicar nisso, irá abrir uma nova guia no seu navegador para o estúdio de IA do Azure ML para o seu recurso em específico. Após isso, você vai clicar no "ML Automatizado" e clicar em novo ML automatizado
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/ff6433c7-9eb9-4f5a-91a6-7f6f7afd85fc)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/9411f926-cc85-4093-b5a4-f6d57833fe1b)
2.1. Para seguir em frente na criação no ML automatizado você deve seguir esses dados das imagens abaixo:
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/4ff6281b-5ad6-4cc4-892d-597de3cd5506)

2.2. Clique em criar para ir para o criar ativo de dados
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/bfb76141-6fbf-401d-b06b-197f826b33c4)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/6dd9702d-834a-4d3d-9e50-54f5767d869d)
2.3. Escolha a fonte de arquivos da Web
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/35c95940-19a7-40a9-a845-f341a88af283)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/5fb510e9-dfd1-4bea-b541-09d4419ed24a)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/436bef68-b181-4af1-8b36-eee5c86d438f)
2.4. Não é necessário alterar nada no esquema. Por último no examinar é somente clicar em criar
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/d6cc7423-8585-418c-a17d-a939c7b70f41)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/111dff95-04e4-4557-bbed-7ae7a5bf9cf6)
3. Criando o tipo de tarefas e dados, é somente selecioná-lo e clicar em avançar
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/0fd05322-04c4-410d-9c85-6863b1e78abd)
4. Clique em Exibir definição de configurações adicionais e o configure dessa forma e depois aperte em salvar: 
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/5a3e26b1-6f13-438c-9ec6-abaff3686003)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/1de7deee-152c-4160-8c1b-bfa79ce86a54)
</br>
5. Clique no limite e acrescente esses valores

![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/8c3318eb-4992-44ce-979b-10538079395b)
</br>
6. No validar e teste acrescente esses valores e clique em avançar

![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/98fc96d4-6a2d-4404-8041-bc4a1a8c4bef)
</br>
7. Não é necessário alterar nada nesses 2, somente avançar e enviar trabalho de treinamento

![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/51a3ec04-d124-4dc0-afec-873beb1653cf)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/b23dd82a-00de-45c5-82fb-1f212b2664bd)

# Finalização
1. Quando finalizar (o status estiver marcado como concluído), clique no melhor resumo de modelo, o link abaixo do nome do algorítmo (caso tenha mais de escolha um que ache melhor)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/f6cc0efb-dc66-4f99-9c46-76224e69319d)
2. Assim, após aparecer a tela do modelo, clique em implantar no "Serviço Web"
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/6a5d1a14-d8be-43e1-a9b1-f60a9fe577ea)

3. Acrescente esses dados e clique em implantar

![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/fb062e57-55cf-408d-b9f2-1dc728330e6a)

4. Assim que terminar tudo (o status ao lado do nome do modelo estiver concluído e o implantar status estiver como êxito), clique no link do implantar status
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/85946c0b-e7e3-4698-9c93-cb58ad12ff7c)
5. Entrando assim no pontos de extremidade, clique em testar e utilize um código semelhante a esse abaixo e pronto, seu desenvolvimento de um componente nessa parte está pronto! Lembrando que o valor de resultado pode estar diferente que o padrão, e não existe problema nisso
<code>
 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }
</code>

![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/9bdd6ee5-e02c-411c-afff-641e25921559)


## Deletando Recurso
Você pode estar me perguntar "por que removê-lo", mas a resposta é simples: qualquer recurso que fica ativo (principalmente a mais que 24 horas) gasta créditos do próprio Azure, acontece que, por quanto mais tempo ele fica, acaba gastando mais desses créditos diariamente, acumulando muito o custo. Além disso, se você estiver usando o Free Trial, caso seus créditos da plataforma acabem, esse custo extra vai diretamente para o cartão cadastrado, o que vai por mim, ninguém merece isso...
</br>
Assim (mesmo não sendo obrigatório no tutorial), irei explicar uma forma de resolver e evitar essa enorme dor de cabeça, que é removendo o recurso
1. Antes de tudo, você deve estar na tela inicial do Portal do Azure, procurar pelo nome grupo de recursos na pesquisa ou em alguma das barras e clicar no Grupo de Recursos em que seu recurso está (normalmente a própria tela de início vai estar disponibilizado isso, como abaixo, mas caso não esteja, essa alternativa anterior também funciona)
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/2576f1fb-0ef7-4efe-aff9-2870491b0766)
2. Entre nesse seu grupo de recurso e clique em Delete resource group ou remover grupo de recurso
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/e2e84e08-1532-49c9-a58c-ea56317b78ff)
3. Por último, confirme o nome do grupo de recursos e remova
![image](https://github.com/GustavoPereira-Dev/Machine-Learning-in-Azure-ML/assets/108029506/4a062e32-bbed-4902-95d9-1b58fc55971e)

Assim, o Azure deletará seu grupo de recursos com seus recursos e você gastará somente o mínimo de crédito para desenvolver o Projeto
</br>
Dessa forma, concluo esse tutorial. Vejo vocês no próximo README!

