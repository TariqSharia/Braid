# Braid

A workday log for people whose day overlaps.

Real workdays don't run one task at a time: you code while a meeting runs,
a colleague asks for help, a quick ticket jumps the queue. Braid records
those overlapping sessions as they happen and shows where the day actually went.

## Features

- **Overlapping sessions:** start work, meeting or help sessions on a project
  or a person, even while another session is running.
- **Two views of the same day:** logged time (every session in full) and
  attributed time (overlaps resolved, so project totals add up to the real day).
- **Context switches and help load:** how often you changed focus, and how much
  time went to helping each colleague.
- **English and Arabic,** with right-to-left layout, from day one.

## Tech stack

NestJS · PostgreSQL (Drizzle ORM) · Next.js · Docker · GitHub Actions

## Roadmap

- [ ] Data model and migrations
- [ ] Sessions API (start, stop, daily view)
- [ ] Overlap and attribution engine, test-first
- [ ] Web app (English / Arabic)
- [ ] CI pipeline, health checks and metrics
- [ ] Cloud deployment (AWS, Terraform)

## Status

Early development.