# Farmers-Marketplace-CRM-Salesforce-Project
Phase 1: Problem Understanding & Industry Analysis

👉 Goal: Build a CRM where farmers list crops, buyers request crops, orders are created, and payments are tracked.
Requirement Gathering
   Farmers list crops (type, price, stock).
   Buyers request crops (Lead → Opportunity).
   Orders must be approved before confirmation.
   Payments are tracked against each order.
Stakeholder Analysis
   Admin: Configures system.
   Farmer (Seller): Lists crops.
   Buyer (Customer): Places requests/orders.
   Sales Agent: Converts leads, manages opportunities, approves orders.
   Manager: Monitors sales, revenue, and disputes.
    Business Process Mapping
Flow:
   Buyer Lead → Opportunity (Crop Request) → Order → Approval → Payment → Invoice/Receipt.
   Industry Use Case Analysis
   Problems: Fraud orders, delayed payments, duplicate buyers.
   Needed: Validation, approval workflows, and payment tracking.
   AppExchange Exploration
   Payment Apps exist (Stripe, PayPal integration), but we’ll build a basic order-payment CRM.
