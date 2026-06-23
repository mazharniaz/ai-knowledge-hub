# Dependencies

node_modules/
**/node_modules/

# Build outputs

dist/
build/
.next/
out/
coverage/

# Environment files

.env
.env.local
.env.development.local
.env.test.local
.env.production.local

# Keep example env files

!.env.example

# Logs

logs/
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*

# OS files

.DS_Store
Thumbs.db

# Editor files

.vscode/*
!.vscode/extensions.json
!.vscode/settings.json
.idea/

# TypeScript

*.tsbuildinfo

# Vite

.vite/

# Cache

.cache/
.parcel-cache/
eslintcache
.eslintcache

# Prisma

backend/prisma/dev.db
backend/prisma/dev.db-journal

# Docker

docker-data/

# Temporary files

tmp/
temp/

# Uploads

uploads/
backend/uploads/

# Production generated files

frontend/dist/
backend/dist/
