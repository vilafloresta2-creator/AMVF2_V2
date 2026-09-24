# Associação Bairro Unido — Independente V2

Sistema reconstruído para funcionar sem Base44: React/Vite + Google Sheets + Google Apps Script + GitHub Pages.

## Google Sheets
Crie uma planilha, abra Extensões → Apps Script, cole `Apps-Script-Code.gs`, salve e execute `setup()` uma vez.

Publique como Aplicativo da Web:
- Executar como: você
- Acesso: qualquer pessoa

A URL da API já está configurada no `src/config.js`.

## Rodar
`npm install`
`npm run dev`

## GitHub Pages
Envie o projeto ao GitHub. O workflow em `.github/workflows/deploy.yml` publica automaticamente.

## Abas
Transactions, Bookings, Residents, Settings.

## Recursos
Dashboard, financeiro com CRUD e CSV, agendamentos por horário, cadastro de moradores e mensalidades, configurações, backup JSON e PWA.
