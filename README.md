# >vanish

A private, self-destructing chat room. Messages disappear. No logs. No history.

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)
![Tailwind](https://img.shields.io/badge/Tailwind-4-38bdf8?style=flat-square&logo=tailwindcss)
![Upstash](https://img.shields.io/badge/Upstash-Redis-00e9a3?style=flat-square&logo=redis)

## ✨ Features

- **Private Rooms** — Create secure chat rooms with unique IDs
- **Self-Destructing** — Messages auto-delete when the room expires
- **Real-time** — Instant message delivery with Upstash Realtime
- **Anonymous** — Random usernames, no accounts needed
- **Room Destruction** — Manually destroy rooms and all messages instantly

## 🛠️ Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Runtime:** Bun
- **API:** Elysia.js
- **Database:** Upstash Redis
- **Real-time:** Upstash Realtime
- **Styling:** Tailwind CSS 4

## 🚀 Getting Started

### Prerequisites

- [Bun](https://bun.sh/) installed
- [Upstash Redis](https://upstash.com/) account

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/real-time-private-chat.git
   cd real-time-private-chat
   ```

2. Install dependencies:

   ```bash
   bun install
   ```

3. Create a `.env` file:

   ```env
   UPSTASH_REDIS_REST_URL=your_upstash_redis_url
   UPSTASH_REDIS_REST_TOKEN=your_upstash_redis_token
   ```

4. Run the development server:

   ```bash
   bun dev
   ```

5. Open [http://localhost:3000](http://localhost:3000)

## 📄 License

MIT

---

<p align="center">
  <i>Messages self-destruct faster than your motivation on a Monday.</i>
</p>
