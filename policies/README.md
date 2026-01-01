# Policies

This directory defines execution authorization policies for Volacore.

## Core Principle

Volacore operates under a strict authority model:

- Default execution state is **DENY**
- No AI action is permitted without an explicit, validated policy
- Policies define *what may execute*, *under which conditions*, and *by whose authority*

## Structure

- `default.policy.md`  
  Defines the global default execution rule.  
  All execution is denied unless explicitly authorized.

## Enforcement

Any execution request not covered by an approved policy
is considered unauthorized and must be rejected.

---

Volacore is an authority layer, not an execution engine.
