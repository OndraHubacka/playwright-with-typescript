# 🎭 Playwright Cheatsheet

---

## ⚙️ Requirements

**Must have 👉 Node.js**

Node.js = prostředí, které umožňuje spouštět JavaScript mimo prohlížeč.

```bash
node --version
npm --version
```

📥 Download:
https://playwright.dev/docs/intro

---

## 🧠 Introduction

Playwright is used for end-to-end testing.

👉 Playwright je nástroj na automatizované testování webových aplikací.

---

## 📦 Install Playwright

```bash
npm init playwright@latest
```

👉 během instalace vyber:
- TypeScript ✅
- Install browsers ✅

---

## 🚀 Run Tests

```bash
npx playwright test
```

---

## 📊 Open HTML Report

```bash
npx playwright show-report
```

---

## 🧪 Useful Commands

### UI mode (interactive runner)
```bash
npx playwright test --ui
```

---

### Run tests in specific browser
```bash
npx playwright test --project=chromium
```

---

### Run specific file
```bash
npx playwright test example
```

---

### Debug mode
```bash
npx playwright test --debug
```

---

### Code generator (auto-create tests)
```bash
npx playwright codegen
```

---

## 💡 Tips

- používej **TypeScript** (lepší autocomplete + méně chyb)
- testy ukládej do složky `tests/`
- používej smysluplné názvy testů

---

## 🧠 TL;DR

```bash
npm init playwright@latest
npx playwright test
npx playwright show-report
```
