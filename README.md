## Microservices E-Commerce App

**Tech Stack:** Consul Discovery, Spring Cloud Config, Gateway, Angular, etc.

**Architecture:**

* **Config Service:** Centralized config with Consul.
* **Customer Service:** Manages customer data (entities, repo, sample data).
* **Gateway Service:** API gateway for routing requests.
* **Inventory Service:** Manages product data (entities, repo, sample data).
* **Order Service:** Manages orders, interacts with Customer & Inventory via Feign.
* **Billing Service:** Shows Consul Config & Vault integration for secrets.
* **Angular Frontend:** UI for managing customers, products, and orders.

**Details:**

* Code snippets and config details in original README.
* Architecture diagram in `captures/capture1.png`.
