# Analytix Pro - SaaS Analytics Dashboard
Modern analytics platform with drag-and-drop dashboards and real-time insights
## Project Structure
```
analytix-pro/
├── 📁 backend/                 # Laravel API
│   ├── app/
│   │   ├── Console/
│   │   ├── Exceptions/
│   │   ├── Http/
│   │   │   ├── Controllers/
│   │   │   │   ├── Api/
│   │   │   │   │   ├── V1/
│   │   │   │   │   │   ├── AuthController.php
│   │   │   │   │   │   ├── EventController.php
│   │   │   │   │   │   ├── DashboardController.php
│   │   │   │   │   │   └── MetricController.php
│   │   │   │   │   └── Admin/
│   │   │   │   └── Web/
│   │   │   ├── Middleware/
│   │   │   └── Requests/
│   │   ├── Jobs/
│   │   │   ├── ProcessEvent.php
│   │   │   └── GenerateInsights.php
│   │   ├── Models/
│   │   │   ├── User.php
│   │   │   ├── Project.php
│   │   │   ├── Event.php
│   │   │   ├── Dashboard.php
│   │   │   └── Widget.php
│   │   ├── Services/
│   │   │   ├── AnalyticsService.php
│   │   │   └── QueryBuilderService.php
│   │   └── Broadcasts/
│   ├── config/
│   ├── database/
│   │   ├── migrations/
│   │   └── seeders/
│   ├── routes/
│   │   ├── api.php
│   │   ├── web.php
│   │   └── channels.php
│   ├── tests/
│   ├── .env.example
│   ├── artisan
│   └── composer.json
│
├── 📁 frontend/                # React + TypeScript
│   ├── public/
│   ├── src/
│   │   ├── api/
│   │   │   ├── client.ts
│   │   │   ├── endpoints.ts
│   │   │   └── websocket.ts
│   │   ├── components/
│   │   │   ├── dashboard/
│   │   │   │   ├── DashboardBuilder.tsx
│   │   │   │   ├── Widget.tsx
│   │   │   │   └── WidgetLibrary.tsx
│   │   │   ├── charts/
│   │   │   ├── layout/
│   │   │   └── ui/
│   │   ├── features/
│   │   │   ├── auth/
│   │   │   ├── events/
│   │   │   └── analytics/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── stores/
│   │   ├── types/
│   │   ├── utils/
│   │   ├── App.tsx
│   │   └── main.tsx
│   ├── package.json
│   ├── tsconfig.json
│   ├── tailwind.config.js
│   └── vite.config.ts
│
├── 📁 docker/                  # Docker configuration
│   ├── nginx/
│   ├── php/
│   └── docker-compose.yml
│
├── 📁 docs/                    # Documentation
│   ├── api/
│   ├── setup/
│   └── deployment/
│
├── 📁 scripts/                 # Utility scripts
├── .gitignore
├── docker-compose.yml
├── LICENSE
└── README.md
```
