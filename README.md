# Ariane — App de Consultório (Agenda, Pacientes e Atendimentos)

Aplicativo Flutter multi-plataforma para gestão de consultório, com foco em:
- **Agenda** (marcação e confirmação de consultas)
- **Cadastro de pacientes** (dados, contatos, histórico)
- **Atendimentos** (evoluções, anexos, procedimentos)
- **Financeiro básico** (recebimentos, formas de pagamento)
- **Notificações** (lembrar consulta, confirmação)

> **Plataformas**: Android, iOS, Web, Windows, macOS e Linux.  
> **Stack base**: Flutter (Dart) Firebase (Auth/Firestore/Functions/Hosting).

## ✨ Funcionalidades

- [x] Estrutura Flutter multi-plataforma
- [x] Agenda com visual diário/semanal
- [x] CRUD de Pacientes
- [x] Registro de Atendimento (com observações e anexos)
- [x] Envio de lembrete de consulta (push/e-mail/SMS/whatsapp) 
- [x] Relatórios simples (consultas por período, faturamento) 

## 🧱 Arquitetura (sugestão)

- **Camadas**: `core/` (erros, models, serviços); `features/` (agenda, pacientes, atendimentos); `app/` (theme, routes).
- **Gerência de estado**: BLoC.
- **Serviços** Firebase Auth, Firestore, Cloud Functions.
