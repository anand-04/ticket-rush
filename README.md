# 🎟️ TicketRush - High-Concurrency Flash-Sale Booking Engine

A high-throughput ticket reservation engine built with **FastAPI**, **PostgreSQL**, and **Redis** designed to handle extreme concurrency, prevent inventory overselling, and manage real-time seat locks.

## 🚀 Key Features
- **Atomic Seat Reservation**: Prevents race conditions during high-demand flash sales using database locking.
- **Temporary Seat Locks**: 5-minute checkout reservation hold backed by Redis TTL.
- **Stress-Tested Architecture**: Benchmarked with simulated concurrent buyers to guarantee data integrity.

## 🛠️ Tech Stack
- **Backend**: Python 3.13, FastAPI
- **Database**: PostgreSQL with SQLAlchemy & Alembic
- **Caching & Locks**: Redis
- **Testing**: Pytest, Locust (Load Testing)
