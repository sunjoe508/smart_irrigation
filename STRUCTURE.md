```
📦 smartfarm-pro/
├── 📁 backend/
│   ├── 📁 api/
│   │   ├── 📁 auth/
│   │   │   ├── 🟢 farmer.auth.js         # ✅ Farmer JWT logic
│   │   │   ├── 🔐 admin.auth.js          # 🔒 Admin auth with 2FA
│   │   │   ├── 🔁 password.recovery.js   # 🔧 Secure reset flow
│   │   │   └── 🧾 audit.logger.js        # 🕵️‍♂️ Login attempt tracking
│   │   ├── 📁 farmer/
│   │   │   ├── 👤 profile.js             # 👨‍🌾 Farmer CRUD
│   │   │   └── 🌾 fields.js              # 🗺️ Field management
│   │   ├── 📁 admin/
│   │   │   ├── 👥 users.js               # 👮 User management
│   │   │   └── 🚨 threats.js             # 🛡️ Security monitoring
│   │   └── 📁 shared/
│   │       └── 🛑 rate.limiter.js        # 🧱 Brute-force protection
│   ├── 📁 models/
│   │   ├── 👨‍🌾 Farmer.js               # 🧬 Extended user schema
│   │   ├── 👨‍💼 Admin.js                # 🏷️ Privileged admin schema
│   │   └── 🔄 Session.js                 # 📌 Active login tracking
│   └── 🚀 app.js                         # 🔗 Auth middleware init
│
├── 📁 frontend/
│   ├── 📁 farmer-app/
│   │   └── 📁 src/
│   │       ├── 📁 auth/
│   │       │   ├── 🔑 Login.vue          # 🌱 Farmer login form
│   │       │   ├── 📝 Register.vue       # 🧾 Farm registration
│   │       │   └── ❓ Forgot.vue         # 🔐 Password recovery
│   │       └── 📁 profile/
│   │           ├── 🛠️ Edit.vue           # 🧑‍🌾 Profile management
│   │           └── 🔐 Security.vue       # 🛡️ 2FA setup
│   ├── 📁 admin-portal/
│   │   └── 📁 src/
│   │       ├── 📁 auth/
│   │       │   ├── 🔐 AdminLogin.vue     # 🚪 Admin auth + IP whitelist
│   │       │   └── 🧾 AuditLog.vue       # 🕵️ Login attempt review
│   │       └── 📁 admin/
│   │           ├── 👤 Users.vue          # 🔧 User management
│   │           └── ⚠️ Alerts.vue         # 🚨 Security notifications
│   └── 📁 shared/
│       ├── 📡 auth.api.js                # 🛰️ Axios auth interceptors
│       └── 🔍 password.validator.js      # 🔑 Zxcvbn strength check
│
└── 📁 automation/
    ├── 📁 auth-tests/                    # 🤖 Postman/Selenium tests
    │   ├── 🌿 farmer-login.json
    │   └── 🔐 admin-2fa.test.js
    └── 📁 security-scans/                # 🧪 OWASP ZAP configs
```
