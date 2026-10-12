# Python-reimplementation-of-the-Vercel-Next.js-App-Router
Sovereign SPA Router Engine. 🏗️ Pure Python. Zero Dependencies. Reimplementing the Next.js App Router architecture for total autonomy. File-based routing, LRU cache, and Priority Prefetching. Proven to run on iPhone (a-Shell). Built by DGK — The System Builder.
<div align="center">
# ⚡ SPA ROUTER ENGINE

### Python reimplementation of the Vercel / Next.js App Router

**Priority queue · LRU cache · Segments · State machine · Live HTTP dashboard**

[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Dependencies](https://img.shields.io/badge/Dependencies-ZERO-success.svg)](#-zero-dependencies)
[![Lines](https://img.shields.io/badge/Lines-1500%2B-blueviolet.svg)](#-architecture)
[![Platform](https://img.shields.io/badge/Platform-a--Shell%20%7C%20Linux%20%7C%20macOS%20%7C%20iOS-lightgrey.svg)](#-installation)

[**Quick Start**](#-quick-start) · [**Features**](#-features) · [**API**](#-http-api) · [**Architecture**](#-architecture) · [**Contributing**](#-contributing)

</div>

---

## 🎯 What is this?

A **pure-Python SPA router** inspired by Next.js App Router internals. No Node.js. No npm. No build step. Just one file that implements:

- File-based routing with dynamic segments
- Nested layouts and route groups
- Prefetch scheduler with priorities
- LRU caches with TTL
- Navigation state machine
- Back/forward history
- Cache busting with SHA-256
- Live HTTP dashboard for testing

Works on **iPhone (a-Shell)**, Linux, macOS, Windows, anywhere Python 3.9+ runs.

---

## ⚡ Quick Start

```bash
# Clone
git clone https://github.com/YOUR_USERNAME/spa-router-engine.git
cd spa-router-engine

# Launch web dashboard
python3 spa_router_engine.py

# Or launch demo mode (terminal only)
python3 spa_router_engine.py demo
