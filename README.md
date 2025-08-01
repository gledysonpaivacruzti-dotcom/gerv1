# 🧾 Abertura de Chamado GLPI

Este projeto fornece uma página web responsiva e interativa para gerar descrições padronizadas de chamados no sistema GLPI, com base em informações como UF, Backbone, tipo de evento, cidades e parceiro.

## ✅ Funcionalidades

- Seleção de cidades com autocompletar
- Identificação automática da UF com base na primeira cidade em ordem alfabética
- Geração dinâmica da descrição no formato padrão GLPI
- Suporte a eventos como: Ruptura, Atenuação, Indisponibilidade, Degradação
- Campo de canal afetado visível apenas em caso de indisponibilidade
- Parceiros padronizados em caixa alta
- Copiar descrição com um clique
- Alerta automático para rompimento com RAMAN

## 🚀 Como usar

1. Clone este repositório ou baixe o arquivo HTML.
2. Abra o arquivo `abertura_chamado_glpi_safe_pontasA_B_final.html` no navegador.
3. Preencha os campos com as informações do chamado.
4. A descrição será gerada automaticamente.
5. Clique no botão 📋 para copiar a descrição.

## 🌐 Deploy via GitHub Pages

Você pode hospedar facilmente esta página com o GitHub Pages:

- Vá em **Settings > Pages**
- Selecione a branch com o HTML
- Pronto! O link será algo como:

```
https://seuusuario.github.io/seu-repositorio/
```

## 🧾 Exemplo de descrição gerada

```
DWDM::CE::IND::CH22::FORTALEZA<>TERESINA::WORK::GIGA+
```

## 👨‍💻 Desenvolvedor

Gledyson Paiva – Fortaleza/CE
