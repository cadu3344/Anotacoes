# Minhas Anotações

**Minhas Anotações** é um aplicativo web simples e intuitivo para criar, organizar e gerenciar anotações, ideal para estudantes que desejam registrar e consultar notas de aulas ou estudos. Com uma interface amigável, o aplicativo permite adicionar notas com formatação rica, filtrá-las por conteúdo ou data, editá-las, excluí-las e exportá-las como PDFs.

## Funcionalidades

- **Criação de Notas:** Adicione notas com matéria, título e conteúdo formatado (suporta texto em negrito, itálico, listas, links e imagens).
- **Edição e Exclusão:** Edite ou remova notas existentes com facilidade.
- **Filtragem:** Filtre notas por matéria, título, conteúdo ou intervalo de datas.
- **Exportação para PDF:** Baixe notas como arquivos PDF com formatação preservada (imagens não incluídas).
- **Persistência Local:** Notas são salvas no navegador usando `localStorage`, garantindo acesso mesmo após fechar a aba.

## Tecnologias Utilizadas

- **HTML5** e **CSS3**: Estrutura e estilização da interface.
- **JavaScript**: Lógica de gerenciamento de notas e interatividade.
- **Quill.js**: Editor de texto rico para formatação avançada.
- **jsPDF**: Geração de arquivos PDF.

## Como Usar

1. **Acesse o Aplicativo:**
   - Clone o repositório: `git clone https://github.com/seu-usuario/minhas-anotacoes.git`
   - Abra o arquivo `index.html` em um navegador moderno.

2. **Crie uma Nota:**
   - Preencha os campos "Matéria" e "Título".
   - Use o editor para inserir o conteúdo, com opções de formatação como listas, negrito e imagens.
   - Clique em "Adicionar Nota".

3. **Gerencie Notas:**
   - Use o campo de filtro para buscar notas por texto.
   - Selecione um intervalo de datas para filtrar por período.
   - Edite, exclua ou baixe uma nota como PDF usando os botões correspondentes.

## Instalação

Não é necessária instalação adicional, pois o aplicativo é executado diretamente no navegador. Basta abrir o arquivo `index.html`. As dependências (Quill.js e jsPDF) são carregadas via CDN.

## Limitações

- As notas são salvas apenas localmente (`localStorage`), sem sincronização entre dispositivos.
- Imagens não são exportadas nos PDFs.
- O aplicativo depende de conexões com CDNs para carregar Quill.js e jsPDF.

## Contribuições

Contribuições são bem-vindas! Para sugerir melhorias ou corrigir problemas:
1. Faça um fork do repositório.
2. Crie uma branch para sua feature: `git checkout -b minha-feature`.
3. Commit suas alterações: `git commit -m 'Adiciona minha feature'`.
4. Envie para o repositório: `git push origin minha-feature`.
5. Abra um Pull Request.

## Licença

[Escolha uma licença, ex.: MIT License]  
Este projeto é de código aberto e pode ser usado livremente conforme os termos da licença.

---

Desenvolvido por Carlos Eduardo da Fonseca Silva Martins
