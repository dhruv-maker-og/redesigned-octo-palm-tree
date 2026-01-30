# Copilot CLI Delegate Demo – Next.js

This repo has been **upgraded to Next.js 15** using GitHub Copilot CLI's **/delegate** flow:
- Successfully upgraded from Next.js 13.5.6 to Next.js 15.x
- Upgraded React from 18.2.0 to 19.x
- All tests passing and build verified
- Demonstrates offloading **framework upgrades** to a **cloud agent**

## What Changed
- ✅ Next.js 13.5.6 → ^15.1.3 (installed: 15.5.11)
- ✅ React 18.2.0 → ^19.0.0 (installed: 19.2.4)
- ✅ @testing-library/react 14.2.1 → ^16.1.0 (React 19 support)
- ✅ TypeScript configuration auto-updated for Next.js 15
- ✅ All builds and tests verified

## Prereqs
- GitHub Copilot subscription with **Copilot CLI** enabled
- Node 22+, npm 10+
- (Optional) Codespaces if you prefer browser-based demo

## Local run
```bash
npm install
npm run dev
```

## Build and Test
```bash
npm run build  # Build production bundle
npm run test   # Run test suite
npm run ci     # Run build + test
```
