# Exercícios em Rust

Este repositório contém uma coleção de exercícios práticos desenvolvidos durante meus estudos da linguagem Rust. O objetivo é consolidar conceitos fundamentais e explorar as funcionalidades da linguagem por meio de exemplos variados e progressivos.

## 📚 Conteúdo

- **Fundamentos:** variáveis, tipos de dados, funções, controle de fluxo.
- **Ownership e Borrowing:** regras de propriedade, referências, slices.
- **Lifetimes:** anotações de tempo de vida.
- **Structs e Enums:** definição e implementação de métodos.
- **Pattern Matching:** uso de `match`, `if let`, `while let`.
- **Tratamento de Erros:** `Option`, `Result`, `panic`, `?`.
- **Coleções:** `Vec`, `HashMap`, `String`.
- **Concorrência:** threads, canais, `Mutex`, `Arc`.
- **Recursos Avançados:** traits, generics, closures, iteradores.
- **Pequenos Projetos:** exercícios integradores (ex: calculadora, CLI simples, leitura de arquivos).

## 🚀 Como usar

1. Certifique-se de ter o Rust instalado. Se não tiver, use [rustup](https://rustup.rs/).
2. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/exercicios-rust.git
   cd exercicios-rust
   ```
3. Navegue até o exercício desejado e compile/execute com Cargo:
   ```bash
   cd nome-do-exercicio
   cargo run
   ```
   Ou, para exercícios que são apenas bibliotecas:
   ```bash
   cargo test
   ```

## 📁 Estrutura

```
.
├── fundamentos/
├── ownership/
├── lifetimes/
├── structs_enums/
├── pattern_matching/
├── erros/
├── colecoes/
├── concorrencia/
├── avancado/
└── projetos/
```

Cada subdiretório contém um ou mais exercícios com seu próprio `Cargo.toml` e código fonte.

## 🛠 Pré-requisitos

- Rust (versão estável mais recente)
- Conhecimento básico de programação

## 📖 Estudos relacionados

Estou seguindo a [documentação oficial do Rust](https://doc.rust-lang.org/book/), o [Rust by Example](https://doc.rust-lang.org/rust-by-example/) e outros materiais.

## 🤝 Contribuições

Este é um repositório de estudo pessoal, mas sugestões e correções são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
