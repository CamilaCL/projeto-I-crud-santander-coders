# **Projeto Transações Bancárias**

## Programa Santander Coders 2024.1 | Turma Data Science | Ada Tech
### *Módulo: Lógica de Programação II*

Este projeto foi desenvolvido como parte do módulo de Lógica de Programação II, curso Data Science do programa Santander Coders 2024.1. O projeto caracteriza um sistema de gestão de transações de uma conta bancária pessoal, permitindo visualizar, criar, editar e excluir transações.

## Descrição do Projeto

O objetivo é desenvolver um sistema CRUD (*Create, Read, Update, Delete*) que gerencia transações financeiras de uma conta bancária pessoal. Cada transação possui um valor, uma categoria e um ID exclusivo (UUID).

### Funcionalidades
- **Visualizar Transações**: Consulte os dados das transações bancárias, como valor, categoria e ID; 
- **Criar Transações**: Adicione novas transações à conta;
- **Editar Transações**: Modifique os detalhes de uma transação existente;
- **Excluir Transações**: Remova transações indesejadas ou incorretas;
- **Relatórios**: Gere relatórios das transações, como valor total ou valor médio, inclusive detalhando por categorias;
- **Persistência de Dados**: Um arquivo JSON simula os dados de transação de uma conta bancária.

#### ***OBS***:  As funções que geram os dados e criam a interface do sistema foram disponibilizadas pelo professor do curso.

## Funções do Programa

As funções abaixo foram implementadas como requisitos do projeto. Além disso, outras funções auxiliares também foram desenvolvidas como suporte a estas funções.

```python
def run():
    """Executa o programa e exibe a tela inicial"""

def visualizar_relatorios():
    """Mostra um menu de opções para gerar relatórios baseados na escolha do usuário"""

def salvar_relatorio():
    """Salva o relatório gerado em formato .txt"""

def calcular_total_transacoes():
    """Calcula o valor total das transações"""

def mostrar_m5_transacoes():
    """
    Mostra as m5 transações realizadas, onde m é um parâmetro:
    - 'max' para os 5 maiores valores
    - 'min' para os 5 menores valores
    - 'median' para os 5 valores medianos"""

def calcular_media():
    """Calcula a média dos valores das transações"""

def consultar_transacao_por_ID():
    """Consulta uma transação específica pelo seu UUID"""

def cadastrar_transacao():
    """Cadastra uma nova transação"""

def editar_transacao_por_ID():
    """Edita uma transação específica pelo seu UUID"""
    pass

def excluir_transacao():
    """Exclui uma transação específica pelo UUID"""
```

## Organização do Projeto

```

santander-coders-projeto-I-crud/
│
├── data/                                 # Dados utilizados pelo projeto
├── reports/                              # Arquivos .txt exemplificando os relatórios salvos
├── src/                                  # Código-fonte do projeto
│   ├── projeto_crud.ipynb                # Notebook principal do projeto
│   ├── Arquivo base do projeto.ipynb     # Notebook disponibilizado pelo professor
├── .gitignore                            # Arquivo para ignorar arquivos e diretórios no Git
├── README.md                             # Arquivo de descrição do projeto

```
