---
title: "技术选型的一些权衡"
date: 2026-02-10
description: "Vite / TS / IndexedDB 这套组合是怎么来的。"
---

## Vite

选 Vite 是因为它的模块热替换做得足够干净，不用为了热更新再去写一堆 polyfill。

## IndexedDB

持久化实验历史，避免刷新后丢掉进度。localStorage 容量太小，IndexedDB 是更合理的选择。

## TypeScript

纯粹为了重构时心里有底。
