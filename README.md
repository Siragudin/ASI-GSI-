# ASI / GSI — Global Innovation Protocols

ASI (AI Semantic Infrastructure) is a semantic middleware protocol for ideas. 
GSI (Global Semantic Infrastructure) is a decentralized transport protocol connecting corporate problem requests with verified solutions. 

Together, they form a **Dual-Loop Layer** that scales global technological cooperation without central monopolies or platform locks. Released under the **MIT License**.

---

## ⚡ High-Level Architecture: The Dual-Loop Model

The core innovation of this ecosystem is the absolute separation of proactive ideas (human creative signal) and formalized problem requests (corporate/institutional needs).

### 🔄 Loop 1: Proactive Ideas (ASI)
*   **Origin:** Individuals or independent teams.
*   **Processing:** Handled entirely at the edge by independent **ASI Nodes**. 
*   **Mechanism:** Translates unstructured text/data into normalized semantic objects. It runs multi-criteria scoring (prioritizing *Mechanism Uniqueness* over surface-level keywords) and handles semantic caching to reduce LLM compute costs.
*   **Privacy:** Strict multi-layer circuit isolation (Identity vs. Reputation vs. Semantics). Analysts review idea logic completely blind to the author's social status or identity.

### 🌐 Loop 2: Problem Requests & Interaction (GSI)
*   **Origin:** Registered and verified Organizations.
*   **Transport:** GSI is a lightweight, permissionless *Transport Protocol* (similar to HTTP/SMTP), not a centralized platform.
*   **Mechanism:** Organizations sign and broadcast standardized **Requests** (Problem Statements + Constraints + Binding Collaboration Terms). 
*   **Zero-Knowledge Trust:** GSI inherits authentication from ASI nodes via API but carries no internal user accounts or central moderation.

---

## 🛡️ Self-Regulation & Anti-Abuse (B2B Circuit)

Unlike traditional networks that rely on global bans or centralized policing, GSI protects itself via **Dynamic Market Self-Isolation**:

1.  **One-Response-Per-Request Constraint:** Prevents mass spamting or automated DDoS on corporate analyst queues at the protocol level.
2.  **Bidirectional Blindness:** If a company blocks a bad actor or a non-compliant ASI node locally, the block is bidirectional. The violator instantly loses visibility of the company’s future requests. Over time, bad actors face total digital blindness within the network.
3.  **One-Way Anonymous Contribution:** Supports a legally clean anonymous mode. Anonymous submissions are structurally verified by ASI but automatically classified as *Public Domain / Free Assistance*, removing patent-ambush risks for enterprise adopters.

---

## 📂 Repository Structure

*   📂 `docs/`
    *   📘 **ASI — Full Book (English):** Core concepts, semantic scoring matrices, identity isolation circuits, and high-load intake queue design.
    *   📗 **GSI — Full Book (English):** Federated trust models, request/response lifecycle schemas, protocol clients, and network self-regulation mechanics.

---
*This architecture is proposed as an open reference design for Microsoft Futures, OpenAI, Google ASI, universities, and sovereign research frameworks to build the open internet of technological progress.*
