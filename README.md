

# Logica_de_Programacao
Um estudo sobre lógica de programação

## Conceitos Fundamentais

A linguagem __C__ é considerada uma linguagem convencional, para promgramar eu uma __linguagem convencional__, é fundamental especificar as áreas de memória em que os dados que queremos trabalhar estão armazenados, e frequentimente considerar os endereços de memória dos dados.

a construção de um programa em __C__ envolve duas fases a compilação e a execução

Compilção: __Pc__ (Programa Fonte) -> compilador -> __Pm__ (Programa Objeto)

Execução: Dados de Entrada -> __Pm__ -> Saída

Na prática o programa fonte e o programa Objeto são armazenados em arquivos em disco, aos quais nos referimos como __Arquivo Fonte e Arquivo Objeto__

na linguagem __C__ não é imposta uma formatação rígida

Existem 2 tipos de ambientes em um código __C__: 

- __Global__, externos as funções
- __Local__, Interno as funções

Um programa em __C__, deve conter obrigatóriamente a função principal (__main__), uma vez que a execução de um programa começa sempre por ela
Comandos e declarações devem ser finalizadas com __;__.

### Ciclo de desenvolvimento

Existem diversas ferramentas utilizadas na construção de programas (editores, compiladores, ligadores). É raro que um programa seja composto de um único arquivo-fonte. Para facilitar os projetos, os programs são divididos em vários arquivos. Eles podem ser compilados separadamente, porém para se obter um programa executavel, é necessário reunir os códigos e suas bibliotecas. Essa é a função do __Ligador__.

Já a tarefa das __Bibliotecas__, é possibilitar acesso facil as funções de interesse geral.

### Verificação e Validação


Outro ponto que deve ser observado é que os programas podem conter erros, que precisam ser identificados e corrigidos. É preciso sempre fazer testes e aplicar conceitos de melhoia continua para melhor funcionamento dos nossos programas.
```
 |editar| -> |compilar| -> |Ligar| -> |Testar|
 
 ```
 Este cilco pode ser aplicado separadamente para cada item ou em um ambiente integrado de desenvolvimento, ou __IDE__.
 
 ## Expressões
 Na linguagém **C**, uma expressão é a combinação de **Variáveis**, **Constantes** e **Operadores** que pode ser avaliada computacionalmente, resultando em um valor. O valor resultante é chamado de **Valor da expressão**.
 
 
 
