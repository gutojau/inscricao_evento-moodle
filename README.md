# inscricao_evento-moodle
Plugin para o Moodle para inscrição em eventos
mod/inscricao_evento/
├── amd/
│   └── build/                # Scripts JS compilados (opcional)
│   └── src/                  # Scripts JS (opcional)
├── classes/
│   └── event/                # Eventos customizados (opcional)
├── db/
│   ├── access.php            # Capabilities (permissões)
│   ├── install.xml           # Estrutura do banco de dados (XMLDB)
│   └── upgrade.php           # Atualizações de banco de dados
├── lang/
│   └── en/
│       └── inscricao_evento.php  # Arquivo de idioma (inglês)
├── pix/
│   └── icon.png              # Ícone da atividade
├── backup/
│   ├── moodle2/
│   │   ├── backup_inscricao_evento_activity_task.class.php
│   │   ├── backup_inscricao_evento_stepslib.php
│   │   ├── restore_inscricao_evento_activity_task.class.php
│   │   ├── restore_inscricao_evento_stepslib.php
├── mod_form.php              # Formulário de configuração da atividade
├── view.php                  # Interface principal da atividade
├── index.php                 # Lista todas as instâncias no curso
├── lib.php                   # Funções principais (eventos, callbacks)
├── version.php               # Versão e informações do plugin
├── locallib.php              # Lógica customizada (ex: envio, verificação)
└── settings.php              # Configurações globais da atividade (opcional)

