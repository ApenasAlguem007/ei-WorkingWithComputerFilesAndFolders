 O que é pathlib?
É uma biblioteca padrão do Python que permite trabalhar com caminhos de arquivos/pastas de um jeito mais moderno e organizado (orientado a objetos), substituindo o os.path.
Vantagens:

Código mais legível
Mais seguro
Funciona melhor entre sistemas (Windows/Linux/Mac)


 O que tem nos exemplos (ex01 → ex11)
Cada arquivo exXX.py é um passo:

Ex01: básicos do Path (criar caminho, ver se existe, pegar nome/extensão, listar pastas)
Ex02: renomear arquivos
Ex03: renomear usando a pasta “pai” como referência
Ex04: criar nomes baseados na hierarquia de pastas
Ex05: renomear com data/timestamp
Ex06: trocar extensão (tipo .txt → .csv)
Ex07: criar vários arquivos automaticamente
Ex08: compactar arquivos em .zip (e opcionalmente apagar os originais)
Ex09: extrair .zip em pastas organizadas
Ex10: buscar arquivos (recursivo) e filtrar pelo nome
Ex11: limpar diretórios (apagar arquivos automaticamente)


 Boas práticas (alertas importantes)

Verificar se é arquivo mesmo (is_file())
Evitar sobrescrever sem querer
Cuidado com comandos destrutivos (unlink())
Ter atenção ao extrair ZIP (segurança/validação)
Evitar caracteres inválidos (especialmente no Windows)


 Caminho de evolução do repositório
Ele segue uma progressão bem lógica:

fundamentos
navegar em pastas
mexer com nomes
automatizar tarefas
casos reais (ZIP, busca, limpeza)


 Ideias para evoluir depois
Você pode transformar isso em:

um programa de terminal (CLI)
organizador automático de downloads
sistema de backup
pipeline de processamento de arquivos