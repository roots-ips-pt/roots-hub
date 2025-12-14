## Primeira versão (0.1.0)

A versão `0.1.0` deve ser publicada quando o projeto já tem **algo que funciona de forma mínima**, mas não o suficiente para ser considerado “estável” ou “completo”.

Ou seja, `0.1.0` = primeira versão minimamente funcional, utilizável de alguma forma, ainda incompleta e sujeita a grandes alterações.

### ✔️ **Resumo rápido**

* funciona minimamente
* estrutura organizada
* qualquer pessoa consegue correr
* preparado para crescer, mas ainda instável

### 🎯 **Critérios mínimos para lançar uma `0.1.0`**

Um projeto deve cumprir pelo menos **3 requisitos base**:

#### **1. Uma funcionalidade principal (mesmo que parcial)**

Não precisa ser completa, mas deve *fazer algo* observável:

* Uma API que responde a 1 endpoint básico
* Uma app web com um único ecrã funcional (login falso, lista vazia, formulário básico)
* Um script que executa a lógica principal apenas em modo demo
* Um hardware que acende LEDs ou lê um sensor de forma básica
* Um jogo que mostra o ecrã inicial e mexe uma sprite
* Um dataset organizado num formato mínimo

> “Faz algo” → demonstra a ideia central e permite testes iniciais.

#### **2. Projeto estruturado (mesmo que simples)**

O repositório deve ter uma estrutura organizada e padronizada:

* README com:

  * descrição curta
  * objetivo do projeto
  * instruções mínimas para compilar/executar
* LICENSE
* .gitignore
* Estrutura de pastas definida (mesmo que alguns ficheiros estejam vazios):

  * `/src`
  * `/docs`
  * `/tests` (opcional mas recomendado)

#### **3. Capacidade de ser executado por outra pessoa**

Outra pessoa deve conseguir correr o projeto com:

* instruções de compilação/execução ou comando (ex: `npm install && npm start`);
* instruções simples (ex: “ligar sensor X ao pino Y e correr script”);
* dependências listadas (`package.json`, `requirements.txt`, etc.)

> [!WARNING]
> Se só o autor consegue “pôr a funcionar”, não está pronto para `0.1.0`.

#### **Bónus desejáveis (mas não obrigatórios)**

Se possível:

* Testes básicos (1 ou 2)
* Demonstração simples (gif, screenshot)

Não são requisitos — apenas boas práticas.

#### ❌ **O que *não* é suficiente para 0.1.0**

Evitar publicar `0.1.0` se só existir:

* apenas README
* código não executável
* protótipos ou mockups sem implementação
* código solto sem estrutura
* documentação sem implementação
* hardware sem firmware
* app ou site estático sem funcionalidade

Portanto, antes de chegar a uma versão `0.1.0`, as modificações efetuadas são descritas na secção  `[unreleased]`.