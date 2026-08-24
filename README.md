<div align="center">

# 👾 Kim Sanghyeok ( sanghyeok03 )

**Offensive Security · Bug Bounty · AI-powered Security Research**

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
name:        Kim Sanghyeok
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

## 🚀 Projects

| Project | Description |
| :--- | :--- |
| 🍯 **LLM Prompt Injection Honeypot** | 프롬프트 인젝션 공격을 허니팟 방식으로 유인·대응하는 모델 제작 *(CMUX × AIM 해커톤)* |
| 🛡️ **Security Monitoring System** | 보안 관제 시스템 설계 및 구현 *(Genspark)* |
| 🏃 **Running App** | 러닝 기록·관리 애플리케이션 개발 |
| 🔮 **오늘의 운세 (fortune-site / myfortune_web)** | 운세 서비스 기획 및 제작 |
| 💥 **CVE-2023-44487 Lab** | HTTP/2 Rapid Reset 취약 환경 구성 및 공격 재현·테스트 |
| 🚩 **CTF** | 다수 대회 참여 (Web / Misc 중심) |

---

## 🐛 Bug Bounty & Vulnerability Research

> 다양한 취약점 클래스를 실제 자산에서 독립적으로 발견·제보한 이력입니다.

### 🏆 Assigned CVEs

| CVE ID | Target | Type | Severity | Description |
| :--- | :--- | :--- | :---: | :--- |
| [**CVE-2026-78280**](https://patchstack.com/database/wordpress/plugin/hash-form/vulnerability/wordpress-hash-form-plugin-1-4-0-cross-site-request-forgery-csrf-vulnerability) | WordPress **Hash Form** Plugin ≤ 1.4.0 | CSRF | ![CVSS 4.3](https://img.shields.io/badge/CVSS-4.3-yellow?style=flat-square) | 비인증 공격자가 인증된 사용자에게 의도치 않은 동작을 강제할 수 있는 CSRF 취약점 발견 · v1.4.1에서 패치 완료 |

### 📋 Reported Vulnerability Classes

`CSRF` · `Clickjacking` · `CORS Misconfiguration` · `Prompt Injection` · `Information Disclosure` · `Arbitrary File Exfiltration` · `IDOR`

<details>
<summary>📋 <b>Disclosure History (펼쳐보기)</b></summary>

<br/>

**Patchstack** — CVE 발급

- [**CVE-2026-78280**](https://patchstack.com/database/wordpress/plugin/hash-form/vulnerability/wordpress-hash-form-plugin-1-4-0-cross-site-request-forgery-csrf-vulnerability) — WordPress Hash Form Plugin ≤ 1.4.0 CSRF 취약점 발견 및 제보 · OWASP A1: Broken Access Control

**HackerOne** — 아래 6건 제보 *(모두 Duplicate 판정 · 유효 취약점 독립 발견)*

- **Clickjacking** — Login/Signup/Password Reset 페이지의 Framing 보호 미비
- **Prompt Injection** — `claude-code-action`의 Context Prompt 내 비정제 XML 태그
- **CORS Misconfiguration** — 임의 Origin이 인증된 GraphQL 요청 수행 가능 *(Netflix)*
- **CORS Misconfiguration** — 임의 Origin 반영 및 자격 증명 허용 *(quicknode testnet RPC)*
- **Information Disclosure** — `debug_traceBlockByNumber` RPC 메서드 노출 *(testnet RPC)*
- **Arbitrary File Exfiltration** — Cache Symlink Escape를 통한 임의 파일 유출

**FinderGap**

- **IDOR** 취약점 제보 *(자체 검증 실수로 제보 취소)*

</details>

---

