Primeiro eu fiz a implantação do modelo.
após ter seguido todo passo a passo em aula (Configurando Modelos e conjunto de Dados) 

Após isso, eu selecionei o "melhor modelo" (VotingEnsemble)
Acessei as métricas e Verifiquei os gráficos "Residuais" e Predito_True

**Implantar e testar o modelo**
Acessei a guia MODELO dentro da opção melhor modelo
Acessei a sub-guia e selecionei "IMPLANTAR" e serviços web e Preenchi as Informações abaixo:

Nome : prever-alugueis
Descrição : Prever aluguel de bicicletas
Tipo de computação : Instância de Contêiner do Azure
Habilitar autenticação : selecionado

E foi impressa a seguinte mensagem de êxito: A implantação de modelo foi disparada com êxito

Agora irei testar o serviço implantado

Selecionei "Pontos de extremidade" e a guia "testar" e fiz a alteração do modelo JSON pelo modelo da documentação

e foi impresso o seguinte resultado ": float 361.95238671338427 "