


Nếu bạn đang tìm kiếm một giải pháp mã nguồn mở để quản lý toàn bộ chuyến đi của mình thay vì dùng hàng chục ứng dụng khác nhau, thì TREK là dự án đáng chú ý nhất mình thấy gần đây.

TREK là một nền tảng trip planner tự host với hơn 7.4k ⭐ trên GitHub, được ví như sự kết hợp giữa Wanderlog, Google Maps, Splitwise và Notion dành riêng cho du lịch.

Điều khiến dự án này nổi bật không phải là lập kế hoạch hành trình đơn thuần mà là khả năng quản lý gần như toàn bộ chuyến đi trong một nơi duy nhất:

• Lập lịch trình theo từng ngày bằng giao diện kéo thả trực quan.
• Hiển thị toàn bộ địa điểm trên bản đồ tương tác.
• Tự động tối ưu tuyến đường di chuyển.
• Tìm kiếm địa điểm từ Google Places hoặc OpenStreetMap.
• Theo dõi ngân sách theo từng danh mục chi tiêu.
• Chia tiền giữa các thành viên giống Splitwise.
• Hỗ trợ đa tiền tệ cho các chuyến đi quốc tế.
• Quản lý vé máy bay, khách sạn, nhà hàng và booking.
• Lưu trữ vé điện tử, PDF và tài liệu chuyến đi.
• Tạo checklist hành lý và theo dõi tiến độ đóng gói.
• Giao việc chuẩn bị hành lý cho từng thành viên trong đoàn.
• Đồng bộ thời gian thực giữa các thành viên.
• Chat nhóm, ghi chú chung và tạo poll biểu quyết.
• Theo dõi thời tiết đến 16 ngày trước chuyến đi.
• Hoạt động offline nhờ hỗ trợ PWA.
• Cài như ứng dụng trên iPhone hoặc Android mà không cần App Store.
• Hỗ trợ đăng nhập Google, Apple, Keycloak và nhiều hệ thống SSO khác.
• Tích hợp MCP Server để AI Agent có thể trực tiếp lên kế hoạch chuyến đi, tạo packing list hoặc quản lý ngân sách tự động.

Điểm mình đánh giá cao nhất là toàn bộ dữ liệu đều nằm trên server của bạn thay vì nằm trên dịch vụ của bên thứ ba. Đây là thứ mà rất ít ứng dụng lập kế hoạch du lịch hiện nay cho phép.

Chỉ với một lệnh Docker, bạn đã có thể triển khai hệ thống trong khoảng 30 giây và sử dụng ngay trên điện thoại hoặc máy tính bảng như một ứng dụng native thực thụ.

Một dự án cực kỳ phù hợp cho:

* Gia đình chuẩn bị đi du lịch.
* Nhóm bạn đi phượt hoặc roadtrip.
* Digital nomad thường xuyên di chuyển.
* Công ty tổ chức team building hoặc công tác.
* Những ai thích self-host và kiểm soát dữ liệu cá nhân.




<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/logo-trek-light.gif" />
  <source media="(prefers-color-scheme: light)" srcset="docs/logo-trek-dark.gif" />
  <img src="docs/logo-trek-dark.gif" alt="TREK" height="96" />
</picture>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/subtitle-light.png" />
  <source media="(prefers-color-scheme: light)" srcset="docs/subtitle-dark.png" />
  <img src="docs/subtitle-dark.png" alt="Your trips. Your plan. Your server." height="28" />
</picture>

A self-hosted, real-time collaborative travel planner — with maps, budgets, packing lists, a journal, and AI built in.

<br />

<a href="https://demo.liketrek.com"><img alt="Demo" src="https://img.shields.io/badge/Demo-try-111827?style=for-the-badge" /></a>
&nbsp;
<a href="https://hub.docker.com/r/mauriceboe/trek"><img alt="Docker" src="https://img.shields.io/badge/Docker-ready-2496ED?style=for-the-badge" /></a>
&nbsp;
<a href="https://discord.gg/NhZBDSd4qW"><img alt="Discord" src="https://img.shields.io/badge/Discord-join-5865F2?style=for-the-badge" /></a>
&nbsp;
<a href="https://kanban.pakulat.org/shared/I4wxF6inOOMB0C6hH6kQm3efyNxFjwyI"><img alt="Roadmap" src="https://img.shields.io/badge/Roadmap-view-0EA5E9?style=for-the-badge" /></a>
<br />
<a href="https://ko-fi.com/mauriceboe"><img alt="Ko-fi" src="https://img.shields.io/badge/Ko--fi-support-FF5E5B?style=for-the-badge" /></a>
&nbsp;
<a href="https://www.buymeacoffee.com/mauriceboe"><img alt="BMAC" src="https://img.shields.io/badge/BMAC-support-FFDD00?style=for-the-badge" /></a>
<br />
<a href="LICENSE"><img alt="License" src="https://img.shields.io/badge/license-AGPL_v3-6B7280?style=flat-square" /></a>
<a href="https://github.com/mauriceboe/TREK/releases"><img alt="Latest Release" src="https://img.shields.io/github/v/release/mauriceboe/TREK?include_prereleases&style=flat-square&color=6B7280" /></a>
<a href="https://hub.docker.com/r/mauriceboe/trek"><img alt="Docker Pulls" src="https://img.shields.io/docker/pulls/mauriceboe/trek?style=flat-square&color=6B7280" /></a>
<a href="https://github.com/mauriceboe/TREK"><img alt="Stars" src="https://img.shields.io/github/stars/mauriceboe/TREK?style=flat-square&color=6B7280" /></a>

</div>

---

<div align="center">

<img src="https://github.com/mauriceboe/trek-media/releases/download/readme-assets/TREK1.gif" alt="TREK — 60-second tour" width="100%" />

</div>

<br />

<div align="center">
  <a href="docs/screenshots/dashboard.png"><img src="docs/screenshots/dashboard.png" alt="Dashboard" width="49%" /></a>
  <a href="docs/screenshots/trip-planner.png"><img src="docs/screenshots/trip-planner.png" alt="Trip planner with 3D map" width="49%" /></a>
  <a href="docs/screenshots/journey.png"><img src="docs/screenshots/journey.png" alt="Journey journal" width="49%" /></a>
  <a href="docs/screenshots/budget.png"><img src="docs/screenshots/budget.png" alt="Costs · expense splitting" width="49%" /></a>
  <a href="docs/screenshots/atlas.png"><img src="docs/screenshots/atlas.png" alt="Atlas · visited countries" width="49%" /></a>
  <a href="docs/screenshots/vacay.png"><img src="docs/screenshots/vacay.png" alt="Vacay planner" width="49%" /></a>
  <a href="docs/screenshots/trip-iceland.png"><img src="docs/screenshots/trip-iceland.png" alt="Trip planner · day plan and route" width="49%" /></a>
  <a href="docs/screenshots/admin.png"><img src="docs/screenshots/admin.png" alt="Admin panel" width="49%" /></a>
</div>

---

## What you get

<picture>
  <source media="(max-width: 700px)" srcset="docs/tiles/grid-mobile.svg" />
  <img src="docs/tiles/grid-desktop.svg" alt="TREK feature tiles" width="100%" />
</picture>

<details>
<summary><b>See all features</b></summary>

<table>
<tr>
<td width="50%" valign="top">

#### 🧭 Trip planning

- **Drag & drop planner** — organise places into day plans with reordering and cross-day moves
- **Interactive map** — Leaflet or Mapbox GL with 3D buildings, terrain, photo markers, clustering, route visualization
- **Place search** — Google Places (photos, ratings, hours) or OpenStreetMap (free, no API key)
- **Place import** — shared Google Maps / Naver Maps lists, plus GPX and KML/KMZ/GeoJSON map files
- **Day notes** — timestamped, icon-tagged notes with drag-and-drop reordering
- **Route optimisation** — auto-sort places and export to Google Maps
- **Weather forecasts** — 16-day via Open-Meteo (no key) + historical climate fallback
- **Category filter** — show only matching pins on the map

</td>
<td width="50%" valign="top">

#### 🧳 Travel management

- **Reservations** — flights, accommodations, restaurants with status, confirmation numbers, files; import from booking confirmation emails and PDFs ([KDE Itinerary](https://invent.kde.org/pim/kitinerary))
- **Costs** — track and split trip expenses (Splitwise-style): per-person / per-day breakdowns, settle-up, multi-currency
- **Packing lists** — categories, templates, user assignment, progress tracking
- **Bag tracking** — optional weight tracking with iOS-style distribution
- **Document manager** — attach docs, tickets, PDFs to trips / places / reservations (≤ 50 MB each)
- **PDF export** — full trip plan as PDF with cover page, images, notes

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 👥 Collaboration

- **Real-time sync** — WebSocket. Changes appear instantly across all connected users
- **Multi-user trips** — invite members with role-based access
- **Invite links** — one-time or reusable links with expiry
- **SSO (OIDC)** — Google, Apple, Authentik, Keycloak, or any OIDC provider
- **2FA** — TOTP + backup codes
- **Passkeys** — passwordless WebAuthn login (fingerprint / face / PIN / security key), admin-toggleable
- **Collab suite** — group chat, shared notes, polls, day check-ins

</td>
<td width="50%" valign="top">

#### 📱 Mobile & PWA

- **Installable** — iOS and Android, straight from the browser, no App Store needed
- **Offline support** — Service Worker caches tiles, API, uploads via Workbox
- **Native feel** — fullscreen standalone, themed status bar, splash screen
- **Touch optimised** — mobile-specific layouts with safe-area handling

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧩 Addons (admin-toggleable)

- **Lists** — packing lists + to-dos with templates, member assignments, optional bag tracking
- **Costs** — expense tracker with splits and settle-up (who owes whom), multi-currency
- **Documents** — file attachments on trips, places, and reservations
- **Collab** — chat, notes, polls, day-by-day attendance
- **Vacay** — personal vacation planner with calendar, 100+ country holidays, carry-over tracking
- **Atlas** — world map of visited countries, bucket list, travel stats, streak tracking, liquid-glass UI
- **Journey** — magazine-style travel journal with entries, photos (Immich/Synology), maps, moods
- **AirTrail** — connect a self-hosted AirTrail instance to import and sync flights into reservations
- **MCP** — expose TREK to AI assistants via OAuth 2.1

</td>
<td width="50%" valign="top">

#### 🤖 AI / MCP

- **Built-in MCP server** — OAuth 2.1 authenticated. 150+ tools, 30 resources
- **Granular scopes** — 27 OAuth scopes across 13 permission groups
- **Full automation** — AI can create trips, plan days, build packing lists, manage budgets, mark countries visited
- **Pre-built prompts** — `trip-summary`, `packing-list`, `budget-overview`
- **Addon-aware** — exposes Atlas, Collab, Vacay when those addons are on

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### ⚙️ Admin & customisation

- **Dashboard views** — card grid or compact list · **Dark mode** — full theme with matching status bar
- **20 languages** — EN, DE, ES, FR, IT, NL, HU, RU, ZH, ZH-TW, PL, CS, AR (RTL), BR, ID, TR, JA, KO, UK, GR
- **Admin panel** — users, invites, packing templates, categories, addons, API keys, backups, GitHub history
- **Notifications** — per-user preferences across email (SMTP), webhook, ntfy, and an in-app notification center
- **Auto-backups** — scheduled with configurable retention · **Units** — °C/°F, 12h/24h, map tile sources, default coordinates

</td>
</tr>
</table>

</details>

<br />

## Get started in 30 seconds

```bash
ENCRYPTION_KEY=$(openssl rand -hex 32) docker run -d -p 3000:3000 \
  -e ENCRYPTION_KEY=$ENCRYPTION_KEY \
  -v ./data:/app/data -v ./uploads:/app/uploads mauriceboe/trek
```

Open `http://localhost:3000`. On first boot TREK seeds an admin account — if you set `ADMIN_EMAIL`/`ADMIN_PASSWORD` those are used, otherwise the credentials are printed to the container log (`docker logs trek`).

<div align="center">

&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#docker-compose-production">Docker Compose</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#helm-kubernetes">Helm / Kubernetes</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#install-as-app-pwa">Install as PWA</a>&nbsp;&nbsp;·&nbsp;&nbsp;<a href="#reverse-proxy">Reverse Proxy</a>&nbsp;&nbsp;·&nbsp;&nbsp;

</div>

<br />

## Tech stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js_22-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS_11-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

Real-time sync via WebSocket (`ws`). Backend on NestJS 11. State with Zustand. Auth via JWT + OAuth 2.1 + OIDC + Passkeys (WebAuthn) + TOTP MFA. Weather via Open-Meteo (no key required). Maps with Leaflet and Mapbox GL.

<br />

<h2 id="docker-compose-production">Docker Compose (production)</h2>

<details>
<summary>Full compose example with secure defaults</summary>

```yaml
services:
  app:
    image: mauriceboe/trek:latest
    container_name: trek
    read_only: true
    security_opt:
      - no-new-privileges:true
    cap_drop:
      - ALL
    cap_add:
      - CHOWN
      - SETUID
      - SETGID
    tmpfs:
      - /tmp:noexec,nosuid,size=64m
    ports:
      - "3000:3000"
    environment:
      - NODE_ENV=production
      - PORT=3000
      - ENCRYPTION_KEY=${ENCRYPTION_KEY:-}   # generate with: openssl rand -hex 32
      - TZ=${TZ:-UTC}
      - LOG_LEVEL=${LOG_LEVEL:-info}
      - ALLOWED_ORIGINS=${ALLOWED_ORIGINS:-}
      - APP_URL=${APP_URL:-}                 # required for OIDC + email links
      # - FORCE_HTTPS=true                   # behind a TLS-terminating proxy
      # - TRUST_PROXY=1
      # - OIDC_ISSUER=https://auth.example.com
      # - OIDC_CLIENT_ID=trek
      # - OIDC_CLIENT_SECRET=supersecret
      # - OIDC_DISPLAY_NAME=SSO
      # - OIDC_ADMIN_CLAIM=groups
      # - OIDC_ADMIN_VALUE=app-trek-admins
    volumes:
      - ./data:/app/data
      - ./uploads:/app/uploads
    restart: unless-stopped
    healthcheck:
      test: ["CMD", "wget", "-qO-", "http://localhost:3000/api/health"]
      interval: 30s
      timeout: 10s
      retries: 3
      start_period: 15s
```

Then:

```bash
docker compose up -d
```

**HTTPS notes:** `FORCE_HTTPS=true` is optional — it adds a 301 redirect, HSTS, CSP upgrade-insecure-requests, and forces the `secure` cookie flag. Only use it behind a TLS-terminating reverse proxy. `TRUST_PROXY=1` tells the server how many proxies sit in front so real client IPs and `X-Forwarded-Proto` work.

</details>

<br />

<h2 id="helm-kubernetes">Helm (Kubernetes)</h2>

```bash
helm repo add trek https://mauriceboe.github.io/TREK
helm repo update
helm install trek trek/trek
```

See [`charts/README.md`](https://github.com/mauriceboe/TREK/blob/main/charts/README.md) for values.

<h2 id="install-as-app-pwa">Install as App (PWA)</h2>

TREK works as a Progressive Web App — no App Store needed.

1. Open TREK in the browser (HTTPS required)
2. **iOS**: Share ▸ *Add to Home Screen*
3. **Android**: Menu ▸ *Install app* (or *Add to Home Screen*)

TREK then launches fullscreen with its own icon, just like a native app.

<br />

## Updating

**Docker Compose:**

```bash
docker compose pull && docker compose up -d
```

**Docker run** — reuse the original volume paths:

```bash
docker pull mauriceboe/trek
docker rm -f trek
docker run -d --name trek -p 3000:3000 -v ./data:/app/data -v ./uploads:/app/uploads --restart unless-stopped mauriceboe/trek
```

> Not sure which paths you used? `docker inspect trek --format '{{json .Mounts}}'` before removing the container.

Your data stays in the mounted `data` and `uploads` volumes — updates never touch it.

> [!IMPORTANT]
> Mount **only** the data and uploads directories — `-v ./data:/app/data -v ./uploads:/app/uploads`. **Never mount a volume at `/app`.** Doing so hides the application code shipped in the image and the container fails to start with `Cannot find module 'tsconfig-paths/register'`. If you previously mounted `/app`, switch to the two mounts above; your data in `data/` and `uploads/` is preserved.

<h3>Rotating the Encryption Key</h3>

If you need to rotate `ENCRYPTION_KEY` (e.g. upgrading from a version that derived encryption from `JWT_SECRET`):

```bash
docker exec -it trek node --import tsx scripts/migrate-encryption.ts
```

The script creates a timestamped DB backup before making changes and prompts for old + new keys (input is not echoed).

<h2 id="reverse-proxy">Reverse Proxy</h2>

For production, put TREK behind a TLS-terminating reverse proxy. TREK uses WebSockets for real-time sync, so the proxy **must** support WebSocket upgrades on `/ws`.

<details>
<summary>Nginx</summary>

```nginx
server {
    listen 80;
    server_name trek.yourdomain.com;
    return 301 https://$host$request_uri;
}

server {
    listen 443 ssl http2;
    server_name trek.yourdomain.com;

    ssl_certificate     /etc/ssl/fullchain.pem;
    ssl_certificate_key /etc/ssl/privkey.pem;

    # 500 MB covers backup-restore uploads (capped at 500 MB server-side).
    client_max_body_size 500m;

    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Host $host;
        proxy_set_header X-Real-IP $remote_addr;
        proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for;
        proxy_set_header X-Forwarded-Proto $scheme;
    }

    location /ws {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection "upgrade";
        proxy_set_header Host $host;
        proxy_read_timeout 86400;
    }
}
```

</details>

<details>
<summary>Caddy</summary>

```caddy
trek.yourdomain.com {
    reverse_proxy localhost:3000
}
```

Caddy handles TLS and WebSockets automatically.

</details>

<br />

## Environment variables

<details>
<summary><b>Full reference</b></summary>

<br />

| Variable | Description | Default |
|----------|-------------|---------|
| **Core** | | |
| `PORT` | Server port | `3000` |
| `NODE_ENV` | Environment (`production` / `development`) | `production` |
| `ENCRYPTION_KEY` | At-rest encryption key for stored secrets (API keys, MFA, SMTP, OIDC). Recommended: generate with `openssl rand -hex 32`. If unset, falls back to `data/.jwt_secret` (existing installs) or auto-generates a key (fresh installs). | Auto |
| `TZ` | Timezone for logs, reminders and cron jobs (e.g. `Europe/Berlin`) | `UTC` |
| `LOG_LEVEL` | `info` = concise user actions, `debug` = verbose details | `info` |
| `DEFAULT_LANGUAGE` | Default language on the login page for users with no saved preference. Browser/OS language is auto-detected first; this is the fallback. Supported: `de`, `en`, `es`, `fr`, `hu`, `nl`, `br`, `cs`, `pl`, `ru`, `zh`, `zh-TW`, `it`, `ar`, `id`, `tr`, `ja`, `ko`, `uk`, `gr` | `en` |
| `ALLOWED_ORIGINS` | Comma-separated origins for CORS and email links | same-origin |
| `FORCE_HTTPS` | Optional. When `true`: 301-redirects HTTP to HTTPS, sends HSTS, adds CSP `upgrade-insecure-requests`, forces the session cookie `secure` flag. Useful behind a TLS-terminating reverse proxy. Requires `TRUST_PROXY`. | `false` |
| `HSTS_INCLUDE_SUBDOMAINS` | When `true`: adds the `includeSubDomains` directive to the HSTS header, extending HTTPS enforcement to all subdomains. Only effective when HSTS is active (`FORCE_HTTPS=true` or `NODE_ENV=production`). Leave `false` if you run other services on sibling subdomains over plain HTTP. | `false` |
| `COOKIE_SECURE` | Controls the `secure` flag on the `trek_session` cookie. Auto-derived: on when `NODE_ENV=production` or `FORCE_HTTPS=true`. Escape hatch: set `false` to allow session cookies over plain HTTP. Not recommended in production. | auto |
| `SESSION_DURATION` | How long a login session stays valid when **"Remember me" is unchecked** (the default): sets the `trek_session` JWT `exp` and issues a browser-session cookie (cleared when the browser closes). Accepts `ms`-style strings: `1h`, `12h`, `7d`, `30d`, `90d`. Invalid values warn at startup and fall back to the default. | `24h` |
| `SESSION_DURATION_REMEMBER` | Session length when **"Remember me" is ticked** at login: a longer-lived JWT plus a persistent `trek_session` cookie that survives browser restarts. Same format and startup-fallback behaviour as `SESSION_DURATION`. | `30d` |
| `TRUST_PROXY` | Number of trusted reverse proxies. Tells the server to read client IP from `X-Forwarded-For` and protocol from `X-Forwarded-Proto`. Defaults to `1` in production; off in dev unless set. | `1` |
| `ALLOW_INTERNAL_NETWORK` | Allow outbound requests to private/RFC-1918 IPs (e.g. Immich on your LAN). Loopback and link-local addresses remain blocked. | `false` |
| `APP_URL` | Public base URL of this instance (e.g. `https://trek.example.com`). Required when OIDC is enabled; used as base for email notification links. | — |
| **OIDC / SSO** | | |
| `OIDC_ISSUER` | OpenID Connect provider URL | — |
| `OIDC_CLIENT_ID` | OIDC client ID | — |
| `OIDC_CLIENT_SECRET` | OIDC client secret | — |
| `OIDC_DISPLAY_NAME` | Label shown on the SSO login button | `SSO` |
| `OIDC_ONLY` | Force SSO-only mode: disables password login + registration, regardless of Admin > Settings. The first SSO login becomes admin. | `false` |
| `OIDC_ADMIN_CLAIM` | OIDC claim used to identify admin users | — |
| `OIDC_ADMIN_VALUE` | Value of the OIDC claim that grants admin role | — |
| `OIDC_SCOPE` | Space-separated OIDC scopes. **Fully replaces** the default — always include `openid email profile`. | `openid email profile` |
| `OIDC_DISCOVERY_URL` | Override the auto-constructed OIDC discovery endpoint (e.g. Authentik: `.../application/o/trek/.well-known/openid-configuration`) | — |
| **Initial setup** | | |
| `ADMIN_EMAIL` | Email for the first admin on initial boot. Must be set together with `ADMIN_PASSWORD`. If either is omitted a random password is printed to the server log. No effect once a user exists. | `admin@trek.local` |
| `ADMIN_PASSWORD` | Password for the first admin on initial boot. Pairs with `ADMIN_EMAIL`. | random |
| **Other** | | |
| `DEMO_MODE` | Enable demo mode (hourly data resets) | `false` |
| `MCP_RATE_LIMIT` | Max MCP API requests per user per minute | `300` |
| `MCP_MAX_SESSION_PER_USER` | Max concurrent MCP sessions per user | `20` |

</details>

<br />

## Data & Backups

- **Database** — SQLite, stored in `./data/travel.db`
- **Uploads** — stored in `./uploads/`
- **Logs** — `./data/logs/trek.log` (auto-rotated)
- **Backups** — create and restore via Admin Panel
- **Auto-Backups** — configurable schedule and retention in Admin Panel

<br />

## Data sources

The Atlas map's country and sub-national (province/county) boundaries come from
[**geoBoundaries**](https://www.geoboundaries.org/) (Runfola et al., 2020), licensed
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See [NOTICE.md](NOTICE.md)
for full third-party attributions.

## License

TREK is [AGPL v3](LICENSE). Self-host freely for personal or internal company use. If you modify and offer TREK as a network service to third parties, your modifications must be open-sourced under the same licence.

