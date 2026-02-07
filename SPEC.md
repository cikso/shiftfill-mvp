# ShiftFill – Phase 1 MVP

## Goal
Fill last-minute construction shifts by contacting workers via SMS.
First worker to reply YES gets the shift.

## Users
- Admin / Dispatcher (office staff)
- Worker (receives SMS, replies YES or NO)

## Core Features (Phase 1)
- Workers
  - name
  - mobile number
  - skills
  - site eligibility
  - active/inactive status
- Sites (construction locations)
- Shifts
  - date
  - start/end time
  - required skill
  - site
  - assigned worker (optional)
- Daily roster view
- Mark worker absent
- Auto-fill shift
  - system finds eligible workers
  - sends SMS in waves
  - first YES locks the shift
- Audit trail of messages and responses

## Tech Stack
- Next.js (App Router) + TypeScript
- Tailwind CSS
- Prisma + PostgreSQL
- SMS via Twilio (later)
