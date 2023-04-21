# LISTA DE TAREFAS

Uma aplicação frontend com HTML, CSS E JS puro para gerir tarefas.
No backend vamos ter uma API NodeJS + Express + MySQL para servir o frontend.

# BASE DE DADOS
    users
        id
        username
        password
        created_at
        update_at
    
    tasks
        id
        id_user
        task_text
        task_status (new | in progress | canceled | sone)
        creates_at
        updated+at

# TREFAS A DESENVOLVER NO PROJETO

    > criar a estrutura inicial
        - base do frontend (html css js | bootstrap)
          - estrutura base de cada página
            - bootstrap (slate) bootswatch
            - fontawesome
        - base do backend (node + express + mysql) cpm uma resposta padrão

    > no frontend
        - páginas necessárias para navegação da nossa aplicação
        - pequenos teste de comunicação entre frontend e backend - utilização de ajax (XMLhttpprequest | fetch API)

    - ver tarefas
        titulo
        filtro para escolher quais tarefas queremos ver (select)
        botão para adicionar tarefas
        (mensagem sobre o fato de não existir tarefas)
        caixa para tarefas
            - possibilidade de alterar o status da tarefa,
            - editar tarefa,
            - eliminar tarefa
        parágrafo com o total de tarefas disponíveis (de acordo com o filtro)

    - adicionar tarefas
        input:text com o texto da tarefa
        botão para cancelar
        botáo para submeter tarefa
    
    - editar tarefa
        input:text para editar o texto da tarefa
        botão para cancelar
        botão para submeter alteração
    
    (eliminar será feito com modal)