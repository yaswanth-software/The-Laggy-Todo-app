# Flutter Architecture & Dart Fundamentals

## 📌 Project Overview

This project explores the core architecture of **Flutter**, Google’s modern framework for building high-performance, cross-platform applications, and the **Dart** programming language that powers it.

By completing this lesson, I gained an understanding of:

- Flutter’s layered architecture
- The widget tree and widget-based UI system
- Reactive rendering using `setState()`
- Essential Dart language features
- How Flutter enables seamless Android and iOS development with a single codebase

---

# 🎯 Objective

To understand Flutter’s architecture, widget-based UI system, and Dart fundamentals for building interactive, reactive, and visually consistent mobile applications.

---

# 🏗️ 1. Flutter Architecture

Flutter is built using three core layers:

## 1️⃣ Framework Layer (Dart)

- Written in **Dart**
- Includes:
  - Material & Cupertino widgets
  - Rendering libraries
  - Animation system
  - Gesture handling

This is where developers write application UI and logic.

---

## 2️⃣ Engine Layer (C++)

- Built using **C++**
- Uses the **Skia graphics engine**
- Handles:
  - Rendering
  - Text layout
  - Platform channels

Flutter renders everything itself instead of relying on native UI components.

---

## 3️⃣ Embedder Layer

- Connects Flutter to platform-specific APIs:
  - Android
  - iOS
  - Web
  - Desktop

It integrates Flutter with the host operating system.

---

## 🔑 Key Concept

Flutter does **not** use native UI components.

Instead, it renders every pixel using the **Skia engine**, which ensures:

- Pixel-perfect UI consistency
- Smooth animations
- Identical design across platforms
- High performance

---

# 🌳 2. Understanding the Widget Tree

In Flutter, **everything is a widget**.

Examples:
- Text
- Buttons
- Layout containers
- Entire screens

Widgets are organized in a hierarchical structure called the **Widget Tree**.

Example structure:


