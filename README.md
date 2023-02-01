# IF707-REDES-NEURAIS



==============


Séries temporais

feed forward 

TDNN
  
  - treinamento 
  - validação -> Para não dá overfiting
  - teste
  
  O teste deve ser feito posteriormente
  
  O erro (alvo-previsto) é usado para o ajuste dos pesos
  
  Base de dados para treino
  
  Transformar um problema temporal em estático

Base de dados Paratreino

<img src="dataT.jpg">

- Recorrente (existe o Feedback)
Cria uma representação de memória usada para verificar contextos históricos de curto tempo. (do instante de tempo anterior)

### A rede de Elman

Pode ser treinado com o backpropagation

Nesse caso o erro é somado em camada e camada de contexto usado para treinar a rede. Não é mais um erro e sim um conjunto de erros somados.

Nesse caso a própria rede criar os parametro de erro.

TDNN - pega uma janela de tempo se você seleciona tempos mais relevantes na janela de tempo você está usando algo mais sofisticado que tdnn.
