# Plano de Testes

## 1 - Objetivo

O objetivo deste plano de testes é garantir que a implementação do backend e frontend do [projeto desenvolvido pela pessoa candidata a vaga de Dev](https://system.devall.com.br/), atenda aos requisitos estabelecidos no desafio técnico proposto a ela.

## 2 - Tipos de teste

O teste escolhido pela empresa para análise do backend e frontend foi a análise funcional (caixa preta).

## 3 - Requisitos a Testar - Backend

1. Implementação correta dos endpoints /post e /post/clique/{id}.
2. Adequação aos requisitos de busca textual, ordenação e registro de clique.
3. Funcionamento apropriado em relação ao banco de dados MySQL de leitura fornecido.

## 4 - Análise Funcional - Backend

1. Texte de Busca Textual
- Cenário: Realizar uma busca textual por um termo específico.
- Ação: Enviar uma requisição GET para /post com um termo de busca.
- Verificação: Certificar-se de que os resultados correspondem ao termo de busca e estão ordenados pela data de publicação em ordem descendente.

2. Teste de Registro de Clique
- Cenário: Simular um clique em um post.
- Ação: Enviar uma requisição GET para /post/clique/{id}.
- Verificação: Garantir que a URL do post seja retornada corretamente e que o clique, seja registrado.

## 5 - Requisitos a Testar - Frontend

1. Funcionalidade correta da interface do usuário.
2. Integração adequada com o backend.
3. Compatibilidade com diferentes navegadores.

## 6 - Análise Funcional - Frontend
1. Teste de Carregamento Inicial
- Cenário: Abrir a aplicação no navegador.
- Ação: Carregar a página inicial.
- Verificação: Confirmar que os últimos posts da aplicação desenvolvida pelo candidato, estejam sendo exibidas corretamente.

2. Teste de Busca por Assunto
- Cenário: Digitar um termo de busca no formulário de pesquisa.
- Ação: Enviar a pesquisa.
- Verificação: Certificar-se de que os resultados da pesquisa correspondem ao termo inserido.

3. Teste de Redirecionamento para Site Externo
- Cenário: Clicar em um link de post.
- Ação: Clicar em um post na lista.
- Verificação: Confirmar que o usuário é redirecionado para o site externo do post.

## 7 - Recursos

- Profissional Analista de QA
- Conhecimento em API Rest
- De 3 a 5 dias úteis
- Computador com acesso a internet, com banda de no mínimo 20MB

## 8 - Ambiente de teste - Software e Hardware

- Sistema Operacional: Windows 11
- Navegadores: Google Chrome - Versão 120.0.6099.225 (Versão oficial) 64 bits e Firefox - Versão 121.0.1 (64-bits)
- [Projeto desenvolvido pela pessoa candidata a vaga de Dev](https://system.devall.com.br/)
- Hardware: Notebook Ideapad 3

## 9 - Ferramenta de teste

- Postman

## 10 - Cronograma

Tipo de teste      | Data de início | Data de término 
-------------------|----------------|---------------------------
Planejar teste     | 17/01/2024     | 17/01/2024
Projetar teste     | 17/01/2024     | 17/01/2024
Implementar teste  | 18/01/2024     | 18/01/2024
Executar teste     | 18/01/2024     | 18/01/2024
Avaliar teste      | 22/01/2024     | 22/01/2024