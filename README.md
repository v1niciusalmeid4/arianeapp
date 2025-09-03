# Ariane — App de Consultório (Agenda, Pacientes e Atendimentos)

Aplicativo Flutter multi-plataforma para gestão de consultório, com foco em:
- **Agenda** (marcação e confirmação de consultas)
- **Cadastro de pacientes** (dados, contatos, histórico)
- **Atendimentos** (evoluções, anexos, procedimentos)
- **Financeiro básico** (recebimentos, formas de pagamento) *(opcional)*
- **Notificações** (lembrar consulta, confirmação) *(opcional)*

> **Plataformas**: Android, iOS, Web, Windows, macOS e Linux.  
> **Stack base**: Flutter (Dart) + (opcional) Firebase (Auth/Firestore/Functions/Hosting).

## ✨ Funcionalidades (MVP)

- [x] Estrutura Flutter multi-plataforma
- [ ] Agenda com visual diário/semanal
- [ ] CRUD de Pacientes
- [ ] Registro de Atendimento (com observações e anexos)
- [ ] Envio de lembrete de consulta (push/e-mail/SMS) *(opcional)*
- [ ] Relatórios simples (consultas por período, faturamento) *(opcional)*

> Marque aqui o que já está pronto e ajuste os itens conforme seu escopo real.

## 🧱 Arquitetura (sugestão)

- **Camadas**: `core/` (erros, models, serviços); `features/` (agenda, pacientes, atendimentos); `app/` (theme, routes).
- **Gerência de estado**: BLoC/Riverpod *(use a que está no projeto)*.
- **Serviços** (opcional): Firebase Auth, Firestore, Cloud Functions.
