> 📘 Este README está disponível em: [🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md)

## 🔐 Exemplo de Criptografia RSA
Implements the RSA encryption algorithm using Python, showcasing key generation, message encryption with public keys, and decryption with private keys.
### Highlights:
- Random prime generation and primality checks
- Calculation of public (`E`) and private (`D`) keys from Euler's totient (`Z`)
- Modular inverse function for computing `E`
- ASCII-based message transformation for encryption and decryption
- Input/output system for user-defined messages and keys
### Useful for understanding RSA fundamentals and experimenting with basic cryptographic logic.

---

## 🚚 Vehicle Load Optimization with Gurobi
Solves a vehicle loading problem using Integer Linear Programming, taking into account maximum weight capacity, product values, available quantities, and incompatibility restrictions.
### Key Features:
- Reads item data from a .txt file (weight, value, quantity, incompatibilities)
- Defines integer (x[i]) and binary (y[i]) decision variables for item inclusion
- Objective function: maximize the total value of the load
- Constraints:
  - Vehicle weight limit
  - Item quantity limits
  - Incompatible item pairs cannot be shipped together
- Displays the optimal solution with selected items and total weight
### Perfect for simulating realistic logistics problems involving constrained selection and value optimization.

---

## 🏭 Factory-to-Client Distribution Optimization with Gurobi
Uses a continuous linear programming model to minimize shipping costs for distributing products from multiple factories to multiple clients, under supply and demand constraints.
### Core elements:
- Reads matrices for factory stock, client demand, and shipping cost per route
- Defines continuous decision variables for quantity shipped
- Objective function: minimize total transportation cost
- Constraints:
  - Each client receives the exact required quantity per product
  - Factories do not exceed their available inventory
- Displays the quantity to be shipped from each factory to each client for each product, along with the optimal distribution cost.
### Outputs the optimal shipping plan by factory, client, and product, and the total cost
