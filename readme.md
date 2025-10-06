# 🧭 OFSC Plugin for Inventory Management

## 📦 Overview
Oracle Field Service Cloud (OFSC) does not provide a complete built-in user interface for managing **on-hand inventory** at the resource (technician) level.  
To address this limitation, the **OFSC Plugin for Inventory Management** provides an easy-to-use, configurable UI that allows dispatchers and resource managers to **view, update, and delete inventory items** directly within OFSC.

This plugin is ready to use — you just need to configure it in your OFSC environment.

---

## 🚀 Features

✅ **View Inventory** — Display all on-hand inventory items for a selected resource.  
✅ **Update Quantity** — Quickly adjust the quantity of an existing inventory item.  
✅ **Delete Item** — Remove a single inventory item from a resource’s on-hand list.  
✅ **Delete All Inventory** — Clear all on-hand inventory items for a resource.  
✅ **Get Resource Details** — Retrieve basic details of a technician or resource.  
✅ **Simple Configuration** — Easy setup in your OFSC plugin configuration section.  

---

## 🧩 Why This Plugin

Oracle Field Service Cloud (OFSC) currently lacks a comprehensive **UI for inventory management**.  
This plugin fills that gap by giving dispatchers and administrators a convenient interface to manage on-hand inventory directly from within OFSC — **without needing complex backend integrations or manual API calls**.

---

## ⚙️ Configuration Steps

1. **Upload the Plugin**
   - Log in to your **OFSC instance**.
   - Navigate to **Configuration → Plugins**.
   - Upload the provided plugin files (HTML, JS, and CSS).

2. **Configure Plugin Settings**
 

3. **Assign to a User Role**
   - Assign the plugin to the **Dispatcher** or **Administrator** role.
   - Ensure the users have permissions to view and modify inventory.

4. **Access the Plugin**
   - Open the plugin from your OFSC interface.
   - Search for a resource (technician) and manage their inventory in real time.

---

## 🧑‍💼 Typical Use Case

- A **dispatcher** needs to correct a technician’s on-hand inventory before assigning new jobs.  
- The dispatcher opens the **Inventory Management Plugin**, selects the technician, adjusts or deletes items, and saves changes instantly — no manual API calls or external tools required.

---

## 🛠️ Technology Stack

- **JavaScript / HTML / CSS**
- **Tailwind CSS** (for styling)
- **OFSC REST APIs**
- **Lightweight & responsive UI**

---



## 🧰 Requirements

- Oracle Field Service Cloud (OFSC) access with **Plugin Manager** enabled  
- REST API access for inventory operations  
- Dispatcher or admin role with edit permissions  

---

## 🎥 Video Tutorial

If you’d like a visual walkthrough of how to configure and use the plugin, check out the video below:

[![OFSC Plugin for Inventory Management Tutorial](https://img.youtube.com/vi/DMH3sp_w3Aw/0.jpg)](https://www.youtube.com/watch?v=DMH3sp_w3Aw)


## 🔒 Notes
- This plugin directly interacts with the OFSC inventory APIs — changes made are **immediately reflected** in your ofsc data.

---

## 📄 License
This plugin is provided as-is under the **MIT License**.  
You are free to modify and extend it for your organization’s needs.

---

## ✉️ Support / Contact
For questions, issues, or improvements, contact the plugin author or your OFSC system administrator.
