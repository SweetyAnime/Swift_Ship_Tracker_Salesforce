# 🚚 SwiftShip Tracker

### Salesforce-Based Parcel Management & AI-Powered Tracking System

SwiftShip Tracker is a Salesforce-based parcel management and tracking system designed to simplify parcel booking, delivery management, shipment tracking, and customer support.

The project combines **Salesforce CRM, Flows, Prompt Builder, Agentforce AI, custom objects, security controls, reports, and dashboards** to provide a centralized parcel management solution with conversational AI assistance.

---

## 📌 Project Overview

Traditional parcel management can involve multiple systems, manual status updates, and dependency on customer support for basic tracking queries.

SwiftShip Tracker addresses these challenges by providing:

- 📦 Centralized parcel management
- 📍 Parcel status and delivery tracking
- 👤 Sender and receiver management
- 🔄 Automated Salesforce Flows
- 🤖 Agentforce-powered conversational tracking
- 🧠 Prompt Builder for AI-powered parcel queries
- 📧 Automated customer notifications
- 📊 Reports and dashboards
- 🔐 Role-based security and access control
- 🌐 Experience Cloud support for customer access

---

## 🎯 Objectives

The main objectives of SwiftShip Tracker are:

1. Centralize parcel and delivery information in Salesforce.
2. Simplify parcel booking and tracking.
3. Automate repetitive parcel-management operations.
4. Provide customers with self-service parcel tracking.
5. Use Agentforce AI to answer parcel-related queries.
6. Provide real-time visibility into parcel status and delivery information.
7. Implement secure, role-based access to Salesforce data.
8. Provide reports and dashboards for operational monitoring.

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      Customers      │
                    │      Senders         │
                    │   Delivery Agents   │
                    │   Support / Admin   │
                    └──────────┬──────────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │ Salesforce Lightning / │
                  │    Experience Cloud    │
                  └───────────┬────────────┘
                              │
                              ▼
                  ┌────────────────────────┐
                  │   SwiftShip Tracker    │
                  │   Salesforce Platform  │
                  └───────────┬────────────┘
                              │
             ┌────────────────┼────────────────┐
             ▼                ▼                ▼
      ┌─────────────┐ ┌─────────────┐ ┌──────────────┐
      │ Parcel      │ │ Delivery    │ │ Sender /     │
      │ Object      │ │ Object      │ │ Receiver     │
      └─────────────┘ └─────────────┘ └──────────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │ Salesforce Flows    │
                   │ Apex / Automation   │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │ Prompt Builder      │
                   │ + Agentforce AI     │
                   └──────────┬──────────┘
                              │
                              ▼
                   ┌─────────────────────┐
                   │ Conversational      │
                   │ Parcel Tracking     │
                   └─────────────────────┘
