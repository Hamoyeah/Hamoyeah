<div align="center">

# 👾 Hamoyeah

**Offensive Security · Bug Bounty · Security Research**

가천대학교 스마트보안전공 · White Hat School 4기

<br/>

![Web Hacking](https://img.shields.io/badge/Web_Hacking-000000?style=for-the-badge&logo=hackthebox&logoColor=9FEF00)
![Bug Bounty](https://img.shields.io/badge/Bug_Bounty-1B1F23?style=for-the-badge&logo=hackerone&logoColor=white)
![CVE](https://img.shields.io/badge/CVE_Hunter-DC143C?style=for-the-badge&logo=cveproject&logoColor=white)
![Reversing](https://img.shields.io/badge/Reverse_Engineering-2D2D2D?style=for-the-badge&logo=ghidra&logoColor=white)
![CTF](https://img.shields.io/badge/CTF_Player-121212?style=for-the-badge&logo=flag&logoColor=red)

</div>

---

## 🧭 About Me

```yaml
name:        Sanghyeok Kim
role:        Security Researcher (in training)
education:   Gachon Univ. — Smart Security (3rd year)
program:     KISA White Hat School 4기  ·  반장(Class Rep)
focus:       [ Web Security, Bug Bounty, Reverse Engineering, AI x Security ]
```
---

## 🛠️ Tech & Tools

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Frida](https://img.shields.io/badge/Frida-C0392B?style=flat-square&logo=frida&logoColor=white)
![IDA](https://img.shields.io/badge/IDA_Pro-1E3A5F?style=flat-square&logo=hexrays&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

</div>

---

## 🏆 Assigned CVEs

| CVE ID | Target | Type | Severity | Description |
| :--- | :--- | :--- | :---: | :--- |
| [**CVE-2026-78280**](https://nvd.nist.gov/vuln/detail/cve-2026-78280) | WordPress **Hash Form** Plugin ≤ 1.4.0 | CSRF | ![CVSS 4.3](https://img.shields.io/badge/CVSS-4.3-yellow?style=flat-square) | 비인증 공격자가 인증된 사용자에게 의도치 않은 동작을 강제할 수 있는 CSRF 취약점 · v1.4.1 패치 |
| [**CVE-2026-103083**](https://nvd.nist.gov/vuln/detail/CVE-2026-103083) | WordPress **ELEX WooCommerce Advanced Bulk Edit** Plugin ≤ 1.5.3 | IDOR (CWE-639) | ![CVSS 5.4](https://img.shields.io/badge/CVSS-5.4-orange?style=flat-square) | 접근 통제를 우회하여 WooCommerce 상품을 무단 삭제할 수 있는 취약점 · v1.5.4 패치 |

---

## 🐛 Bug Bounty & Vulnerability Research

`CSRF` · `Missing Authorization` · `TLS Hostname Verification`

### 📋 Disclosure History

**Patchstack** — CVE 발급

- [**CVE-2026-78280**](https://nvd.nist.gov/vuln/detail/cve-2026-78280) — Hash Form CSRF 취약점 발견 및 제보
- [**CVE-2026-103083**](https://nvd.nist.gov/vuln/detail/CVE-2026-103083) — ELEX WooCommerce Advanced Bulk Edit 상품 무단 삭제 IDOR 취약점 발견 및 제보

**Pagelayer** 
- [**Pagelayer 2.2.0 Missing Authorization**](https://pagelayer.com/blog/pagelayer-v2-2-1-launched/) — 관리자 소유 페이지를 무단 영구 삭제할 수 있는 취약점 발견 및 제보
  
**Widget Options**
- Pending Patch - Widget Options - Remote Code Execution (RCE) -

**Files.com**
- **Java SDK / MuleSoft Connector TLS Hostname Verification** — 잘못된 hostname 인증서를 허용할 수 있는 취약점 발견 및 제보 · **Java SDK 및 MuleSoft Connector 패치** ·

**X / xAI**
- **Android 사진 접근 권한 우회 및 이미지 노출 취약점** — X 앱의 사진 권한을 악용한 이미지 접근 취약점 발견 및 HackerOne 제보

**Vercel** 
- **Turborepo Cache Symlink Escape / Arbitrary File Disclosure** — 외부의 민감 파일이 원격 cache에 포함될 수 있는 취약점 발견 및 제보

**Circle**
- **Arc Testnet RPC Debug Method Exposure** — 인증 없이 상세 EVM execution trace를 조회할 수 있는 구성 발견 및 제보
- **Arc Testnet RPC CORS Misconfiguration** — 임의 Origin 반영과 credential 허용이 함께 적용된 CORS 설정 오류 발견 및 제보
