# Ruben Prod Studio CRM

A web CRM I designed and built for **Ruben Prod**, a photography and videography studio covering weddings and Bar/Bat Mitzvah events in France and Israel. The team uses it every day, and it holds **220+ client files**.

> **Note:** this is a client project, so the source code and data are private. This page presents what the application does.

![Home screen](screenshots/home.jpg)

## What it does

The CRM covers the studio's whole workflow, in five modules:

| Module | What it handles |
|---|---|
| **Gestion** | All events of the year in one table (date, venue, client, photographers, videographers, drone, photo booth…), color-coded by country (France, Israel, abroad), with search, filters and CSV export |
| **Clients** | One file per couple or family: reference date updated automatically from the main event, checklist (quote sent, deposit received, team confirmed…), quote total and remaining balance in EUR and ILS, notes and comments |
| **Devis** | Quotes sent, signed and pending, with deposits and payments recorded per file |
| **Équipe** | Vendors and team members, wedding expenses, and video editing follow-up per file (editor, rate, payment and editing status) |
| **Financier** | Revenue, net results and cash flow |

### Inside a client file

- **Events:** each file groups its events (civil ceremony, henna, pool party, wedding…), each with its own date, venue, country and team.
- **Team assignment:** assign photographers, videographers and other operators to each event, and send them availability requests.
- **Planning:** build the day-of schedule for each event, preview it as a PDF and send it to the client by WhatsApp.
- **Finances:** quotes, deposits, expenses and imported quote PDFs.
- **Auto-save:** every change is saved automatically and shared live with the whole team.

## Technologies

- JavaScript, HTML, CSS
- Real-time shared database, so every team member sees changes instantly
- Year-based organization (2026, 2027…) and bulk import of existing spreadsheets

## My role

I gathered the needs directly from the studio team, designed the workflow and the interface, built the application, and keep improving it based on their daily feedback.

## Author

Shirel Azeroual · Computer Science student, SCE
