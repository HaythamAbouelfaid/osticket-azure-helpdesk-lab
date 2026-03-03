# Architecture & Workflow

## Architecture
- Azure Ubuntu VM hosts:
  - Apache (web server)
  - MySQL (database)
  - osTicket (ticketing platform)
- NSG inbound allowed:
  - 22 (SSH) restricted to admin IP (recommended)
  - 80/443 for HTTP/HTTPS (public)

## Workflow
1. User submits ticket via Support Center
2. Help Topic routes ticket to correct Department queue
3. Agent triages (internal note), investigates, and responds (public reply)
4. SLA tracks response/resolution targets by priority
5. Ticket is resolved/closed with documented verification
6. Metrics dashboard summarizes performance + recurring issues
