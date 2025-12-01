# Cursor-Coding-Rule
This repo is about cursor coding rule how to make it more effective

cursor-repo-template/
├── package.json
├── tsconfig.json
├── .eslintrc.cjs
├── .prettierrc
├── .prettierignore
│
├── apps/
│   ├── frontend/
│   │   ├── package.json
│   │   ├── tsconfig.json
│   │   └── src/
│   │       ├── app/
│   │       │   └── (routes, page.tsx, layout.tsx)
│   │       ├── modules/
│   │       │   └── user/
│   │       │       ├── components/
│   │       │       │   └── UserCard.tsx
│   │       │       ├── hooks/
│   │       │       │   └── useUser.ts
│   │       │       ├── services/
│   │       │       │   └── user.service.ts
│   │       │       ├── api/
│   │       │       │   └── user.api.ts
│   │       │       ├── utils/
│   │       │       ├── types.ts
│   │       │       └── index.ts
│   │       ├── shared/
│   │       │   ├── components/
│   │       │   ├── hooks/
│   │       │   ├── utils/
│   │       │   └── types/
│   │       └── lib/
│   │           └── http.ts
│   │
│   └── backend/
│       ├── package.json
│       ├── tsconfig.json
│       └── src/
│           ├── app.ts
│           ├── server.ts
│           ├── config/
│           │   ├── db.ts
│           │   └── env.ts
│           ├── core/
│           │   └── http/
│           │       └── register-routes.ts
│           ├── modules/
│           │   └── user/
│           │       ├── controllers/
│           │       │   └── user.controller.ts
│           │       ├── services/
│           │       │   └── user.service.ts
│           │       ├── repositories/
│           │       │   └── user.repository.ts
│           │       ├── models/
│           │       │   └── user.model.ts
│           │       ├── validators/
│           │       │   └── user.schema.ts
│           │       ├── types.ts
│           │       └── index.ts
│           └── utils/
│
└── packages/
    └── shared/
        ├── package.json
        └── src/
            └── index.ts

