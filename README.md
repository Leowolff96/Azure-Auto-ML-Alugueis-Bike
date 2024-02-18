
# Criando um Espaço de Trabalho do Aprendizado de Máquina do Azure

Este guia fornecerá instruções passo a passo para criar um espaço de trabalho do Aprendizado de Máquina do Azure e utilizar o aprendizado de máquina automatizado para treinar um modelo de previsão de aluguel de bicicletas.

## Passo 1: Provisão do Espaço de Trabalho do Aprendizado de Máquina

1. Acesse o [Portal do Azure](https://portal.azure.com) utilizando suas credenciais da Microsoft.
2. Selecione "+ Criar um recurso" e procure por "Aprendizado de Máquina".
3. Crie um novo recurso de Aprendizado de Máquina do Azure com as seguintes configurações:
   - **Assinatura:** Sua assinatura do Azure.
   - **Grupo de Recursos:** Crie ou selecione um grupo de recursos.
   - **Nome:** Insira um nome exclusivo para o seu espaço de trabalho.
   - **Região:** Selecione a região geográfica mais próxima.
   - **Conta de Armazenamento:** Observar a nova conta de armazenamento padrão.
   - **Cofre de Chaves:** Observar o novo cofre de chaves padrão.
   - **Application Insights:** Observar o novo recurso padrão de insights de aplicativo.
   - **Registro de Contêiner:** Nenhum (será criado automaticamente na primeira implantação de um modelo em um contêiner).
4. Selecione "Revisar + Criar" e, em seguida, "Criar".

## Passo 2: Utilizando o Aprendizado de Máquina Automatizado

1. Após a criação do espaço de trabalho, selecione "Iniciar Estúdio" no portal do Azure ou acesse [https://ml.azure.com](https://ml.azure.com) e entre no Estúdio do Aprendizado de Máquina do Azure usando sua conta da Microsoft.
2. Feche todas as mensagens exibidas.
3. No Estúdio, verifique se seu espaço de trabalho recém-criado está visível.
4. Caso não esteja, selecione "Todos os Espaços de Trabalho" no menu à esquerda e escolha o espaço de trabalho criado anteriormente.

## Passo 3: Treinamento do Modelo

1. No Estúdio, acesse a página de ML automatizado (em "Criação").
2. Crie um novo trabalho de ML automatizado com as configurações fornecidas no texto original.

## Passo 4: Revisão do Melhor Modelo

1. Quando o trabalho de aprendizado de máquina automatizado for concluído, reveja o melhor modelo treinado conforme as instruções fornecidas.

## Passo 5: Implantação e Teste do Modelo

1. Na guia "Modelo", implante o melhor modelo treinado como um serviço da web com as configurações fornecidas.
2. Aguarde até que a implantação seja bem-sucedida.
3. Teste o serviço implantado conforme instruído.
