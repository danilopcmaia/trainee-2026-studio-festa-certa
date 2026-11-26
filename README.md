# Studio Festa Certa

Plataforma de convites digitais e confirmação de presença para casamentos organizados pelo Studio Festa Certa. A aplicação reúne em um só lugar o convite de cada casal e a lista de convidados, facilitando o acompanhamento das confirmações e o planejamento do evento.

## Escopo

### Incluído

- Convite virtual personalizado com nomes dos noivos, data, local e mapa.
- Página para o convidado confirmar presença e informar o número de acompanhantes.
- Área de gestão de convidados para a cerimonialista:
  - Adicionar, editar e remover convidados.
  - Consultar o status de confirmação.
  - Visualizar as respostas recebidas.
- Identidade visual alinhada ao Studio Festa Certa, com tons de rosa-claro e dourado.
- Layout adaptado para celular, considerando o acesso pelo WhatsApp.

### Fora do escopo inicial

- Envio automático de convites por WhatsApp ou e-mail.
- Controle de mesas e lugares.
- Integração com buffet, pagamentos ou outros serviços.
- Múltiplos níveis de acesso para equipes.

## Stack

- **Frontend:** React + Vite, com componentes reutilizáveis, layout responsivo e identidade visual em rosa-claro e dourado.
- **Backend:** .NET Core / C#, com API REST para operações CRUD e regras de negócio.
- **Banco de dados:** PostgreSQL, para relacionar eventos, convidados e confirmações.
- **Deploy:**
  - **Frontend:** Vercel
  - **Backend:** Render
  - **Banco de dados:** Supabase
