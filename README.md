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
