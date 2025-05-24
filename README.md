# 🤖 AI-Powered Hotel Management System

![Android](https://img.shields.io/badge/Platform-Android-green)
![Java](https://img.shields.io/badge/Language-Java-blue)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)
![AI](https://img.shields.io/badge/AI-Vertex_AI-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

![Cover Image](./assets/cover/ai_hotel_cover.png)

---

## 📱 Overview

The **AI-Powered Hotel Management System** is a dual-application Android solution designed to modernize the traditional hotel experience. It consists of:

- A **User App** that supports:

  - Normal table/menu ordering system
  - AI-powered **Text-based Assistant**
  - AI-powered **Voice-based Assistant**

- An **Admin App** for:
  - Table status management
  - Live order tracking and status updates

All data is managed in real-time with **Firebase**, and AI experiences are powered by **Google Vertex AI**.

---

## 🚀 Features

### 👤 User App

- Firebase Authentication
- Three Ordering Modes:
  - ✅ Traditional
  - 💬 AI Text Assistant
  - 🎙️ AI Voice Assistant
- Real-time Menu & Table Availability
- Dynamic Order Summary & Status
- View & Cancel Orders
- Voice interaction using Vertex AI

### 🔧 Admin App

- Admin Login
- Table Occupancy Management (Green/Red Status)
- Real-time Order Monitoring
- Update Order Status: Pending → In Progress → Served → Cancelled

---

## 🧠 System Flow

### 🔹 Normal Hotel Management System

1. **Login / Signup**
2. **Select Table**
3. **Choose Category & Items**
4. **Place Order or Clear Menu**
5. **Receive Confirmation**  
   ✔️ _“Thank you! Your order has been placed successfully…”_

---

### 💬 AI Text Hotel Management

Conversational AI Guides the User:

- `Hello! How may I assist you today?`
- Select table → Category → Item → Quantity
- Confirm order after full summary

Example:
`Would you like to place this order? (yes/no)`

---

### 🎙️ AI Voice Hotel Management

- Voice interactions via mic button
- Speak actions like:
  - “Book a table”
  - “Show Chinese menu”
  - “Order 2 Chow Mein”
- Real-time voice-to-action with dynamic UI feedback

---

### 🛠️ Admin Dashboard

- Authenticate with Admin credentials
- View & change table statuses (Red = Occupied, Green = Available)
- Monitor orders placed by all users
- Change Order Status dynamically

**Note:**  
Users can cancel only **pending** orders.  
If status is “In Progress” or beyond:
`“Sorry, you can't cancel this order now. Please visit the reception.”`

---

## 🔗 Technologies Used

| Technology       | Purpose                           |
| ---------------- | --------------------------------- |
| Java             | Core App Development              |
| Android Studio   | Development Environment           |
| XML              | UI Design                         |
| Firebase Auth    | User Authentication               |
| Firebase RTDB    | Real-time Database (Menu, Orders) |
| Firebase Storage | Asset Storage (optional)          |
| Vertex AI        | AI Text + Voice Assistant Backend |
| Gradle           | Build Automation                  |

---

## 📸 Screenshot Gallery

### 👤 User App

**🔐 Authentication & Welcome**

| ![Authentication Screen](./assets/screenshots/1_user_authentication.jpg) | ![Welcome Page](./assets/screenshots/2_welcome_page_user_app.jpg) |
| :----------------------------------------------------------------------: | :---------------------------------------------------------------: |

**🪑 Table Selection & 🧾 Category/Item Selection**

| ![Table Selection](./assets/screenshots/3_table_selection.jpg) | ![Category and Item Selection](./assets/screenshots/4_category_item_selection.jpg) |
| :------------------------------------------------------------: | :--------------------------------------------------------------------------------: |

**✅ Order Success & 📋 View Orders**

| ![Order Success](./assets/screenshots/5_order_success.jpg) | ![View Orders](./assets/screenshots/6_show_orders_user.jpg) |
| :--------------------------------------------------------: | :---------------------------------------------------------: |

**❌ Cancel Order Option & 💬 AI Text Mode Home**

| ![Cancel Order Option](./assets/screenshots/7_cancel_order_option.jpg) | ![AI Text Home Screen](./assets/screenshots/8_ai_text_home.jpg) |
| :--------------------------------------------------------------------: | :-------------------------------------------------------------: |

---

### 💬 AI Text-Based System

**🪑 Select Table & 📋 Choose Category**

| ![AI Text - Table Selection](./assets/screenshots/9_ai_text_table_selection.jpg) | ![AI Text - Category Selection](./assets/screenshots/10_ai_text_category_selection.jpg) |
| :------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: |

**🍜 Select Items & 🧾 Order Summary**

| ![AI Text - Item Selection](./assets/screenshots/11_ai_text_item_selection.jpg) | ![AI Text - Order Summary](./assets/screenshots/12_ai_text_order_summary.jpg) |
| :-----------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |

**✅ Post Order Message & 🎙️ Switch to Voice Mode**

| ![AI Text - Post Order Message](./assets/screenshots/13_ai_text_post_order.jpg) | ![AI Voice Home and Table Screen](./assets/screenshots/14_ai_voice_home_and_table.jpg) |
| :-----------------------------------------------------------------------------: | :------------------------------------------------------------------------------------: |

---

### 🎙️ AI Voice-Based System

**📋 Choose Category & 🍲 Select Item**

| ![AI Voice - Category Selection](./assets/screenshots/16_ai_voice_category_selection.jpg) | ![AI Voice - Item Selection](./assets/screenshots/17_ai_voice_item_selection.jpg) |
| :---------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: |

**🔢 Choose Quantity & 🧾 Summary**

| ![AI Voice - Quantity Selection](./assets/screenshots/18_ai_voice_quantity_selection.jpg) | ![AI Voice - Order Summary](./assets/screenshots/19_ai_voice_order_summary.jpg) |
| :---------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: |

**✅ Post Order Message and show Orders after Placing**

| ![AI Voice - Post Order](./assets/screenshots/19_ai_voice_order_summary.jpg) | ![AI Voice - Summary Confirmation](./assets/screenshots/20_ai_voice_post_order.jpg) |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------------: |

---

### 🔧 Admin App

**🔐 Admin Home & 🟩 Table Management**

| ![Admin Main Page](./assets/screenshots/21_admin_main.jpg) | ![Manage Tables](./assets/screenshots/22_manage_tables.jpg) |
| :--------------------------------------------------------: | :---------------------------------------------------------: |

**🟥 Update Table Status & 🗂️ Table Overview**

| ![Update Table Status](./assets/screenshots/23_update_table_status.jpg) | ![Table Overview](./assets/screenshots/24_tables.jpg) |
| :---------------------------------------------------------------------: | :---------------------------------------------------: |

**📋 View Orders & ✏️ Update Order Status**

| ![View All Orders](./assets/screenshots/25_all_orders_admin.jpg) | ![Update Order Status](./assets/screenshots/26_update_order_status.jpg) |
| :--------------------------------------------------------------: | :---------------------------------------------------------------------: |

**📈 Orders After Update & Extra Orders**

| ![Orders After Update](./assets/screenshots/27_orders_after_update.jpg) | ![Additional Order 1](./assets/screenshots/28_additional_order_1.jpg) |
| :---------------------------------------------------------------------: | :-------------------------------------------------------------------: |

| ![Additional Order 2](./assets/screenshots/29_additional_order_2.jpg) | ![Additional Order 3](./assets/screenshots/30_additional_order_3.jpg) |
| :-------------------------------------------------------------------: | :-------------------------------------------------------------------: |

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🙌 Acknowledgements

- Google Firebase for Realtime DB & Auth
- Google Vertex AI for conversational and voice AI
- Android Developers for robust development tools
- Your dedication to building a futuristic hotel solution! 🚀

---
