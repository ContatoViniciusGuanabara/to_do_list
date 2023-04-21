# LISTA DE TAREFAS

## BASE DE DADOS ##
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
