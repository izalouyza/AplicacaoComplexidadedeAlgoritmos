# Aplicação Prática de Complexidade de Algoritmos

Esse repositório refere-se ao trabalho da segunda unidade da disciplina de Estrutura de Dados I. O sistema é destinado a analisar o tempo de resposta de execução de dois tipos de algoritmos de Busca e Ordenação: Bubble Sort e Quick Sort, na implementação de uma Agenda Telefônica. 

---
## 👨‍👧‍👧 Autores

👨‍🏫 **Professor:** George Felipe Fernandes Vieira

👩‍🎓 **Discentes:**  
🔹 [Izadora Louyza Silva Figueiredo](https://github.com/izalouyza)  
🔹 [Lívian Maria Lucena Gomes Pinheiro](https://github.com/livianlucena)  
🔹 [Maria Vitória Fernandes Rocha](https://github.com/tivitoriarocha)  
🔹 [Renato Vitor Juvêncio Leite](https://github.com/infreavek)  
🔹 [Victor Hugo de Oliveira](https://github.com/Victor350br)

---

## 1. Funcionalidades

A aplicação de Agenda Telefônica terá as seguintes funcionalidades:

| Funcionalidade             | Características                                                                 |
|----------------------------|-------------------------------------------------------------------------------|
| **Cadastro de contatos**   | Permite adicionar um novo contato à agenda.                                  |
| **Exibir contatos**        | Exibe todos os contatos cadastrados, organizados alfabeticamente.           |
| **Atualizar contato**      | Permite modificar os dados de um contato já existente.                       |
| **Excluir contato**        | Remove um contato da agenda com base no índice informado.                    |
| **Encerramento do programa** | O sistema pode ser finalizado pelo usuário ao selecionar a opção "Sair".    |

## 2. Como o sistema funciona?

O usuário terá acesso a uma interface interativa onde poderá visualizar as funcionalidades disponíveis e interagir com o sistema. 

### 2.1 Exemplo de Fluxo de Uso

- **Cadastre alguns contatos** inserindo nome, número, e-mail e endereço (opção 1).
- **Exiba a lista de contatos** para visualizar os contatos cadastrados (opção 4).
- **Atualize um contato** caso precise modificar alguma informação (opção 3).
- **Remova um contato** da agenda caso não seja mais necessário (opção 2).
- **A lista de contatos será ordenada automaticamente** antes da exibição:
  - No primeiro código, o **Bubble Sort** será utilizado.
  - No segundo código, o **Quick Sort** será utilizado.
- **Ao finalizar, saia do sistema** (opção 5).

### 2.2 Estrutura de pastas

```
AplicacaoComplexidadedeAlgoritmos/
│
├── AplicacaocomBubble.c      
├── AplicacaocomQuick.c       
│
└── README.md                             
                
```
- **AplicacaocomBubble**: arquivo que contém o exemplo prático utilizando Bubble Sort.
- **AplicacaocomQuick**: arquivo que contém o exemplo prático utilizando Quick Sort.

### 2.3 Funcionamento do sistema

A aplicação de Agenda Telefônica permite que o usuário realize as seguintes ações:

```
================== Agenda telefônica ==================

[1] Cadastrar 
[2] Excluir 
[3] Atualizar 
[4] Exibir 
[5] Sair
>> O que deseja fazer? 

```
#### Menu principal do sistema:
- **Cadastrar**: o sistema permite cadastrar um novo contato na agenda.  
- **Excluir**: o sistema permite remover um contato da agenda.  
- **Atualizar**: o sistema permite atualizar as informações de um contato já cadastrado.  
- **Exibir**: o sistema permite exibir os contatos da agenda.  
- **Sair**: o sistema é encerrado. 

### 3. Como compilar e executar o sistema

Para compilar e executar o sistema, siga os passos abaixo:

1. Primeiramente, certifique-se de ter um ambiente que suporte a linguagem C e um compilador (por exemplo, GCC).
   
2. Clone o repositório do projeto:

```
git clone https://github.com/izalouyza/AplicacaoComplexidadedeAlgoritmos
```

3. Acesse a pasta do repositório:
   
```
cd AplicacaoComplexidadedeAlgoritmos
```

4. Compile os dois programas para testar: 

```
gcc -o agendabubble AplicacaocomBubble.c
```
```
gcc -o agendaquick AplicacaocomQuick.c
```

5. Execute os programas:
   
```
.\agendabubble
```
```
.\agendaquick
```

