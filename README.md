---

![License](https://img.shields.io/badge/license-MIT-blue)

---

# AephOS

AephOS is an experimental operating system built from firmware upward.

The project focuses on architectural sovereignty, beginning at the UEFI layer and evolving toward a fully independent kernel architecture known as AKS (Aephestus Kernel System).

AephOS is designed to explore controlled system evolution, custom memory management, filesystem research (AEPFS), and long-term structural independence from existing operating system ecosystems.

---

## Current Status

Foundational development stage.

* UEFI application builds successfully using EDK2
* Boot verified on real hardware
* Loader architecture in early structuring phase
* AKS kernel bootstrap under design

This project is experimental and not intended for production use.

---

## Architecture Overview

AephOS is structured into the following components:

* **Loader** — UEFI-based boot layer responsible for memory discovery and AKS loading
* **AKS** — Aephestus Kernel System (in early development)
* **AEPFS** — Custom filesystem research (conceptual stage)
* **Aephestus (.aeph)** — Future hybrid language for unified UI and system development

---

## Goals

* Transition from firmware-dependent execution to kernel sovereignty
* Establish a controlled memory management model
* Develop modular system foundations
* Build a long-term architecture capable of independent evolution

---

## Repository Structure

```
/loader/   UEFI boot layer
/aks/      Kernel development
/docs/     Architectural notes and design decisions
/tools/    Auxiliary tooling
```

---

## Build

Currently focused on EDK2-based UEFI loader development.

Further build instructions will be documented as the AKS bootstrap stabilizes.

---

AephOS is an evolving systems engineering initiative.

---

