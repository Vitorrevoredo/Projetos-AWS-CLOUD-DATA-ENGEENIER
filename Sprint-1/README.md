# Instruções

<p>Nessa Sprint o objetivo foi desenvolver um script automatizado que gerasse backups de vendas e relatórios diários com base em um arquivo .csv fornecido. Além disso, consolidamos os relatórios em um arquivo final após a execução de 4 dias de processamento contínuo. O projeto foi executado no ambiente Linux, utilizando scripts em Bash.</p>

## Objetivos da Sprint:

- Criar scripts para automatização do processo de backup de vendas.
- Gerar relatórios diários com os dados coletados.
- Consolidar os relatórios ao final de 4 dias de execução.
- Utilizar `crontab` para agendar a execução automática.

---

## Informações

<p>Durante o desenvolvimento dessa Sprint, foram utilizados diversos comandos e ferramentas do sistema operacional Linux para manipulação de arquivos e geração de relatórios. Entre os principais comandos e métodos utilizados, destacam-se:</p>

- **cut**: para extrair colunas específicas do arquivo .csv.
- **head** e **tail**: para selecionar as primeiras e últimas linhas de um arquivo.
- **sort**: para ordenar os registros com base em diferentes critérios.
- **zip** e **rm**: para compactar e remover arquivos, respectivamente.
- **crontab**: para agendar a execução automática dos scripts.

---

## Anotações

<p>Durante o processo de desenvolvimento, fiz algumas observações importantes:</p>

- O uso de caminhos absolutos no script facilita a execução sem depender da localização do usuário no sistema.
- Tratamento de datas: O uso do `cut` e `sort` para trabalhar com datas foi essencial para garantir que o primeiro e o último registro fossem corretamente identificados.
- Criação de relatórios incrementais: A execução diária dos scripts gerava novos backups e relatórios sem sobrescrever os arquivos anteriores.
- Compactação automática: O uso de `zip` permitiu garantir que os arquivos de backup ocupassem menos espaço e fossem devidamente armazenados.
- Peguei como base os cursos da Udemy e foi pesquisando mais sobre os assuntos por outros métodos de pesquisa, como foruns e vídeos no Youtube
---

## Exercícios

<p>Não teve exercícios nessa Sprint.</p>

---

## Evidências

<p>Coloquei as evidências na pasta específica e também marquei as imagens no README. Além disso, incluí screenshots que ajudam a ilustrar o processo de desenvolvimento.</p>

### Estrutura de Diretórios
<img src="/Sprint-1/Evidencias/exemplo_pastas.png" alt="Estrutura de Pastas" width="600px">

### Execução do Script
<img src="/Sprint-1/Evidencias/Evidencia_de_arquivo_sh_executavel.png" alt="Arquivo sh Executável" width="600px">

### Configuração do Crontab
<img src="/Sprint-1/Evidencias/crontab final.png" alt="Crontab Configurado" width="600px">

### Consolidação de Relatórios
<img src="/Sprint-1/Evidencias/consolidador_versao1.png" alt="Versão 1 do Consolidador" width="600px">

---

## Certificados

<p>Os Certificados da Sprint foram dos Cursos da Udemy, não anexei pois fomos informados que não tinha necessidade.</p>

---

## Comentários Finais

<p>A automação de processos no Linux foi um grande aprendizado, especialmente no uso de crontab e scripts Bash para manipulação de arquivos. Esse conhecimento será fundamental para desafios futuros e projetos mais complexos.</p>
