# VIRA – The Clutch Connection

> **Smart Resource Allocation for NGOs**
> Data-Driven Volunteer Coordination for Social Impact

## 🎯 What is VIRA?

VIRA is a centralized platform that helps NGOs and local organizations:
- **Aggregate** scattered community data (surveys, field reports)
- **Prioritize** urgent community needs using analytics
- **Match** volunteers to tasks based on skills, location & availability



## 🧠 Smart Matching Algorithm

The matching engine scores volunteers for each task:

```
Match Score = (Skill Match × 50) + (Location Match × 30) + (Availability × 20)
```

- **Skill Match (50%)**: % of required skills the volunteer has
- **Location Match (30%)**: Same city = 100%, different = 20%
- **Availability (20%)**: Full-time = 100%, Weekdays = 70%, Weekends = 50%

## 🎨 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 19, Vite 6, React Router 7 |
| Styling | Vanilla CSS (custom design system) |
| Backend | Node.js, Express 4 |
| Auth | JWT (jsonwebtoken + bcryptjs) |
| Database | In-memory store (zero setup) |
| Charts | Custom CSS bar & donut charts |

## 📱 Pages

1. **Landing** — Hero, features, how-it-works, impact stats
2. **Login** — Email/password with demo quick-login
3. **Register** — Role-based (volunteer with skills/location, admin with org)
4. **Volunteer Dashboard** — Stats, assigned tasks, nearby tasks, notifications
5. **Volunteer Tasks** — Assigned/completed tabs
6. **Admin Dashboard** — Overview stats, task breakdowns, quick actions
7. **Task Management** — Filter, search, smart match
8. **Create Task** — Form with category, urgency, skill requirements
9. **Task Detail** — Full info, assignment, match modal
10. **Data Upload** — Submit surveys/reports, view history
11. **Analytics** — Bar charts, donut charts, key insights
12. **Map View** — Location pins with urgency colors
13. **Volunteer List** — Filterable table
14. **Settings** — Profile, language, account

---

Built with ❤️ for social impact.
