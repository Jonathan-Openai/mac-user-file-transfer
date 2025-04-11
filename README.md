# mac-user-file-transfer
A macOS script for copying files from one user to another on the same computer while preserving access for both accounts. Designed for account transitions such as contractor-to-FTE conversions.

# 🔄 macOS User File Transfer Tool (Contractor ➝ FTE)

A macOS script for copying files from one user account to another on the same computer **while preserving access for both accounts**.  
Designed specifically for use cases like **contractor-to-FTE conversions**, where the new account should inherit all previous data, but the original user (contractor) still requires access until deletions.

---

## 🧠 Why Use This?

When a contractor is converted to a full-time employee, it's common to create a new user account (e.g. with a new email). This script:

- ✅ Copies all files from the contractor account to the FTE account
- ✅ Assigns ownership to the FTE
- ✅ Preserves full access for the original contractor
- ❌ Does not delete or alter the original contractor's home folder

---

## 📋 Use Case Example

- **Contractor account:** `jane.contractor@c-openai.ccom`  
- **FTE account:** `jane.doe@openail.com`

Instead of manually dragging files and re-permissioning folders, this script automates the entire process while keeping both users happy and compliant.

---

## ⚙️ Requirements

- macOS (Ventura or later recommended)
- Admin access (`sudo`)
- Both user accounts created before running the script

---

## 🚀 How to Use

1. **Download the script:**

```bash
curl -O https://raw.githubusercontent.com/your-username/mac-user-transfer-tool/main/copy_user_files.sh
