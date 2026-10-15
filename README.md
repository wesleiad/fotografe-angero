# Fotografe - Angerô

Programa da **Suíte Angerô**, o pacote de criação do **Grupo Angerô**.

Edição de imagens com camadas, máscaras e estilos; abre e salva PSD.

- Ajuda: https://github.com/wesleiad/Suite-Angero/blob/main/docs/ajuda/fotografe.md
- Suíte Angerô (iniciador, assistente de IA, instaladores): https://github.com/wesleiad/Suite-Angero
- Versões compiladas: aba **Releases** deste repositório (a Suíte Angerô se atualiza sozinha a partir delas).

## Compilar

Windows, com Rust (MSVC) e Visual Studio Build Tools (C++):

```
cargo build --release --locked -p photocraft -p photocraft-cli
```

Gera `target/release/fotografe.exe` e `target/release/fotografe-cli.exe`.
A cada push no ramo `angero`, o GitHub Actions compila e publica uma versão nova em Releases.

## Código-base e licença

Desenvolvido por Weslei Domingues (TI) para o Grupo Angerô, a partir do código aberto do
**PhotoCraft** (projeto ArtCraft, https://github.com/storytold/photocraft), usado como base.
Licença: MIT OU Apache-2.0, à escolha — veja `LICENSE-MIT`, `LICENSE-APACHE` e `NOTICE`.
