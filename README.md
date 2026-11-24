# Sync-In: SSG Admin Command Suite & Faculty Portal
### University Event Tracking & Attendance Verification (Himamat 2026 & Strands of Love)

An enterprise-grade, high-throughput desktop & tablet administrative operations suite designed specifically for **Supreme Student Government (SSG) Marshals**, **Faculty Evaluators**, and **Event Gate Directors**.

---

## 🚀 Live Access Portals
* **💻 Admin & Faculty Operations Suite**: [https://dunkedoreo-cloud.github.io/sync_in_admin/](https://dunkedoreo-cloud.github.io/sync_in_admin/)
* **📱 Student Universal Smart-Pass (Mobile)**: [https://dunkedoreo-cloud.github.io/sync-in/](https://dunkedoreo-cloud.github.io/sync-in/)

---

## ⚡ Core Operational Capabilities

### 1. 🛡️ Turnstile Telemetry & Gate Flow Control
* Real-time aggregate count of campus attendees across all entry gates.
* Visual capacity gauge with warning thresholds and check-in velocity tracker.
* Instant gate cut-off enforcement and manual turnstile override lock.

### 2. 📋 Live Attendance Registry
* Fast, filterable attendee registry with sub-millisecond search across Student ID, Name, College, and Gate Checkpoint.
* Filter by status: `Enrolled`, `Timed In`, `Timed Out`, `Excused`, and `Flagged`.
* Detailed student inspection drawer with dynamic clearance status and academic history.

### 3. 📷 Optical QR Scanner & UBYTeS Hardware Tap Station
* Integrated web camera viewfinder with optical laser scanline for scanning rotating TOTP QR passes.
* Low-latency UBYTeS hardware tap station simulation for physical student ID cards and dead-phone fast-track lanes.

### 4. 📊 Batch CSV Import & Export
* Comprehensive CSV attendee roster import with format auto-detection and data sanitization.
* Instant CSV attendance ledger export for official university dean's office submissions.

### 5. 📢 Safety Protocol Emergency Broadcast
* Rapid safety alert dispatcher across all active gates and kiosks.
* Broadcast priority overrides: `Normal Operations`, `Gate Congestion Warning`, `Emergency Weather Protocol`, and `Security Gate Lockdown`.

### 6. 🔐 Cryptographic Security Sentinel & Audit Chain
* Immutable SHA-256 block ledger tracking all scans, overrides, and security events.
* Tamper-evident hash chaining with zero-trust validation preventing duplicate scans or replay attacks.

---

## 🔑 Default Access Credentials
| Portal | Role | Identifier | Passcode |
| :--- | :--- | :--- | :--- |
| **SSG Admin Command** | Lead Marshal | `admin@university.edu.ph` | `SSG-2026` |
| **Faculty Portal** | Evaluator | `prof.delacruz@university.edu.ph` | `FACULTY-2026` |

---

## 🛠️ Local Development & Deployment

```bash
# 1. Clone repository
git clone https://github.com/dunkedoreo-cloud/sync_in_admin.git
cd sync_in_admin

# 2. Run local server
node server.js
# Access at http://localhost:3000
```

---

## 📄 Compliance & Governance
* **Republic Act 10173**: Compliant with the Philippine Data Privacy Act of 2012.
* **Architecture**: Zero-trust stateless cryptographic token validation with SHA-256 hash ledger.
* **License**: MIT Permissive License.
