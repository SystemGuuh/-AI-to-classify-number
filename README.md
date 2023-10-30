# Objetivos da IA

### Implementação de MLP (Multilayer Perceptron) sem Bibliotecas Especializadas

- Implementar uma rede neural artificial Multilayer Perceptron (MLP) sem fazer uso de bibliotecas especializadas em redes neurais artificiais.
- Uma camada escondida será utilizada.
- Treinamento com o algoritmo Backpropagation na versão de Gradiente Descendente.

#### Conjuntos de Dados para Treinamento e Teste

- Conjuntos de dados OR, AND e XOR para testes rápidos de correção de implementação.
- Conjunto de dados CARACTERES referente ao exercício do livro da L. Fausett, incluindo versões limpas e com ruídos.

#### Estrutura dos Dados

- Nos problemas de portas lógicas, a última coluna representa o rótulo, enquanto as demais são atributos descritivos.
- No problema dos caracteres, as sete últimas colunas compõem o rótulo, permitindo diferentes abordagens na composição dos valores para a construção do rótulo.

#### Arquivos de Saída

- Arquivo com os hiperparâmetros da arquitetura da rede neural e hiperparâmetros de inicialização.
- Arquivo contendo os pesos iniciais da rede.
- Arquivo com os pesos finais da rede.
- Arquivo contendo o erro cometido pela rede neural em cada iteração do treinamento.
- Arquivo com as saídas produzidas pela rede neural para cada dado de teste.

---

### Implementação de CNN (Convolution Neural Network) com TensorFlow

- Implementar uma rede neural artificial Convolution Neural Network (CNN) com várias camadas escondidas e uma camada densa no final da estrutura.
- Utilizar o conjunto de dados MNIST para testar a rede neural.

#### Tarefas para o Conjunto de Dados MNIST

- Tarefa multiclasse: A rede neural deve responder corretamente para todos os números.
- Tarefa de classificação binária: A rede deve ser treinada para reconhecer apenas dois números selecionados. Os pares de números podem variar durante os testes.

#### Implementação da CNN

- A implementação pode ser feita com um framework à escolha do grupo.
- O grupo pode optar por usar os dados brutos ou características extraídas, como descritor HOG, LBP, Histograma de Blocos ou a transformada wavelet de Haar. Uma das abordagens deve ser apresentada obrigatoriamente, enquanto apresentar ambas é benéfico para a avaliação do trabalho.

#### Arquivos de Saída

- Arquivo contendo os hiperparâmetros da arquitetura da rede neural e hiperparâmetros de inicialização.
- Arquivo com os pesos iniciais da rede.
- Arquivo contendo os pesos finais da rede.
- Arquivo com o erro cometido pela rede neural em cada iteração do treinamento.
- Arquivo com as saídas produzidas pela rede neural para cada dado de teste.

Para mais informações sobre o conjunto de dados MNIST, acesse: [MNIST Dataset](https://www.tensorflow.org/datasets/catalog/mnist?hl=pt-br)
