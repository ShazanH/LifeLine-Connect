# Lifeline Connect

Lifeline Connect is a Node.js-based project designed to manage blood inventory and facilitate seamless connections between donors, hospitals, and organizations. This application ensures a streamlined and efficient process for blood donation and inventory management.

---

## Features

1. **Inventory Management**:
   - Track blood units (`in` for incoming donations and `out` for outgoing usage).
   - Categorization based on blood groups (e.g., O+, AB-, etc.).
   - Detailed associations with donors, hospitals, and organizations.

2. **User Roles**:
   - **Admin**: Manages the system and oversees operations.
   - **Organization**: Maintains inventory and coordinates donations.
   - **Hospital**: Requests and receives blood units.
   - **Donor**: Registers and donates blood.

3. **Dynamic Schema Validations**:
   - Context-based requirements for user and inventory fields.
   - Automated validation for essential fields like email, phone, and addresses.

4. **Time Tracking**:
   - Timestamps to track record creation and updates.

---

## Tech Stack

- **Backend**: Node.js with Express.js.
- **Database**: MongoDB (via Mongoose ODM).
- **Validation**: Mongoose schema-level validations.

---
