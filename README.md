# Change-Validation-Intelligence

**Change Validation Intelligence (CVI)** is an enterprise engineering concept for understanding change impact, determining required validations, and tracking evidence before release.

## Problem

Complex enterprise changes can affect multiple services and business workflows. Teams need to know:

* What could be affected?
* What needs to be validated?
* Why is each validation required?
* What evidence already exists?
* What is still missing before release?

## Concept

**Change → Impact → Validation → Evidence → Release**

CVI brings these steps together around a single change.

## Prototype

The prototype explores a fictional banking engineering scenario where an API change in `TradeIntegrationService` affects:

* Risk Service
* Reconciliation Service
* Reporting Pipeline

The workflow includes:

1. **Change Review** — change summary and validation status
2. **Change Details** — API changes and impact reasoning
3. **Impact Map** — downstream systems and dependencies
4. **Validation Plan** — required validations and rationale
5. **Evidence & Readiness** — evidence status and release decision

The completed workflow reaches:

**Approved — Ready for Release**

## Screenshots

![image alt](https://github.com/MANASA-D-PROJECTS/Change-Validation-Intelligence/blob/0a5891a64f03d1d97ee2a08abd938d61dbe81a6a/CVI%20Workflow.jpg)
![image alt](https://github.com/MANASA-D-PROJECTS/Change-Validation-Intelligence/blob/7f0013094ab8132fbdf510f68eb74258ba396db6/CVI%20Validation.png)


## Core Principle

> **Understand the impact of a change, know what to validate, and see whether you have enough evidence to release.**

CVI is designed as a decision and evidence layer across existing engineering workflows—not as another code scanner, test runner, monitoring platform, or chatbot.

## Prototype Note

All banking, Murex MX.3, service, and dependency data shown are **fictional examples created for product exploration**.

## Status

**Concept / research prototype** — built to explore and validate the underlying enterprise engineering problem.
