🎨 Easy Tatto
Easy Tatto é uma plataforma desenvolvida para conectar pessoas interessadas em fazer tatuagens com tatuadores e estúdios de tatuagem. O sistema facilita a descoberta de artistas por estilo, localização e portfólio, além de oferecer espaço para que novos tatuadores se destaquem e estúdios apresentem sua equipe.

📌 Objetivo do Projeto
Resolver o problema comum de quem deseja fazer uma tatuagem, mas não sabe com quem realizá-la. Easy Tatto permite que:

Clientes encontrem tatuadores por estilo e localização.

Tatuadores iniciantes ou experientes mostrem seu trabalho e recebam contatos.

Estúdios de tatuagem apresentem seus tatuadores associados e serviços.

⚙️ Funcionalidades
Cadastro e login para tatuadores, estúdios e clientes.

Criação de perfil de tatuador com foto, bio, estilos, localização e redes sociais.

Criação de perfil de estúdio com apresentação e tatuadores vinculados.

Upload e exibição de portfólio de tatuagens com imagens.

Página de busca com filtros (estilo, cidade, estúdio).

Vínculo de tatuadores a estúdios de tatuagem.

Contato direto com o tatuador via WhatsApp ou Instagram.

Estrutura pensada para expansão futura (agendamentos, avaliações, favoritos, etc).

🛠️ Tecnologias Utilizadas
🔹 Frontend
React com Vite (desempenho otimizado)

Tailwind CSS para estilização moderna e responsiva

Comunicação com backend via API REST (JSON)

🔹 Backend
Node.js com Express.js

Prisma ORM para modelagem de dados e acesso ao banco

JWT para autenticação de usuários

Multer para upload de imagens (portfólio)

🔹 Banco de Dados
PostgreSQL como banco relacional robusto

Modelagem com relacionamentos entre:

Tatuadores e estúdios (n:n)

Portfólios e estilos

Usuários (clientes, tatuadores, estúdios)

🗂️ Estrutura de Banco (resumida)
usuarios – login e dados gerais

tatuadores – informações de perfil e estilos

portfolio – imagens e descrições de tatuagens

estudios – dados do estúdio e localização

tatuador_estudio – relação tatuador ↔ estúdio

agendamentos (em planejamento)

📌 Status
🔧 Em desenvolvimento – reformulação completa do projeto com foco em estruturação limpa, modular e escalável.
📈 Próximas etapas: sistema de busca por filtros, painel de administração e agendamento.
