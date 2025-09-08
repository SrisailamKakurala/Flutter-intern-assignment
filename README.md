# 📱 Flutter Intern Assignment

---

## 🎯 Task Overview

You need to build a **Flutter app** that includes a page replicating the **Shopify Product Variants** section (mobile view).

The app should have:

* **AppBar navigation** with at least 3 pages:

  * `Home` (allowed to keep the page empty)
  * `Store` (allowed to keep the page empty)
  * `Products` (this is the main task page)

* The **Products Page** should replicate Shopify’s product variant functionality (mobile view).

---

## 🛠 Steps

1. **Login to a free Shopify merchant account**

   * Go to [Shopify Free Trial](https://www.shopify.com/free-trial)
   * Login and go to **Products → Add Product → Scroll to Variants section**
   <img width="1401" height="802" alt="image" src="https://github.com/user-attachments/assets/3c8e756e-61d1-4e17-ad21-24a8796c84a0" />

2. **Observe carefully**

   * Switch to **mobile view** (browser dev tools → toggle mobile mode).
   * Check how Shopify allows adding options (e.g., Size, Color, Material).
   * Notice how variants are generated automatically when you enter multiple values.
   * Check how Price, Inventory, and Img upload fields behave per variant.
   * Make sure to clone the variant component exactly with all functionalities.
   <img width="1047" height="743" alt="image" src="https://github.com/user-attachments/assets/9a19dfbd-55d7-4d63-8519-cf3898877047" />


3. **Implement in Flutter**

   * Create a **Variants Page** in your app that mimics Shopify’s behavior exactly:

     * Ability to add options (e.g., Size, Color)
     * Generate a variant table/list automatically based on option combinations
     * Each variant should allow fields like **Price, Inventory, Img, etc**
     * Ensure smooth scrolling and responsive design

---

## 📐 Requirements

* Use **Flutter BLoC** for state management
* Apply **Clean Architecture** (separation of layers: Presentation, Domain, Data)
* Write **scalable, production-level code**
* Ensure **testability & maintainability** (show how you’d structure code for real apps)

---

## 📦 Submission

* Push the code to a **public GitHub repo**
* Share the repo link with us
* Include a short **README** explaining:

  * Your folder structure
  * How to run the project
  * Any assumptions you made

---

## ⏳ Deadline

Please complete and submit within **2 days** (i.e. 10/09/25 12:30 PM IST) of receiving this assignment.

---

## ✅ Evaluation Criteria

* Clean Architecture implementation
* BLoC usage & state handling
* Code readability & organization/modularity
* UI/UX replication accuracy (compared to Shopify mobile view)
* Extra points for test cases

---

👉 Once you submit, we’ll review the code and get back to you for the next round.

---
