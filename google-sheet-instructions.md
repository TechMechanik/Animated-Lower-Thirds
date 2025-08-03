## 📝 UUFF OBS Overlay – Instructions for Use

**Welcome!**
This Google Sheet is designed to make it easy for presenters and staff to input content for the UUFF OBS Overlay.

After entering your content, click the **📤 Export to JSON** button to the right to generate the file needed by the UUFF Tech Team.

---

### ✅ What This Sheet Does

* Organizes overlay content into logical tabs for each screen quadrant
* Helps guide consistent data entry
* Automatically generates a correctly formatted `.json` file for use in OBS

---

### 📋 Instructions Per Tab

| Sheet Name       | What Goes Here                                                                                                                                           |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Top-Left**     | Enter the content for the **Top Left** corner of the overlay. <br>Includes fields like `top-left-name-*` and `top-left-value-*`.                         |
| **Top-Right**    | Enter content for the **Top Right** overlay section, such as announcements or donation info.                                                             |
| **Bottom-Left**  | Typically includes speaker names or song titles for the **Bottom Left** of the screen.                                                                   |
| **Bottom-Right** | Usually includes lyrics or short-form text displayed in the **Bottom Right** of the overlay.                                                             |
| **Default**      | These values are managed by the Tech Team and control appearance, fonts, spacing, and default values. You usually do **not** need to edit anything here. |

---

### 🧾 Data Entry Format

Each sheet has **two columns**:

* **Key** — the internal field name (e.g. `bottom-left-name-1`)
* **Value** — the content that will be shown in the overlay (e.g. `Eric Stoddard`)

> 🔒 **The “Key” column is protected** to prevent accidental edits.
> Please only update the **“Value” column** unless instructed otherwise.

---

### 🚫 Protected Fields

To keep things running smoothly:

* The `Key` column is **locked**
* The `Default` tab contains preset values that should not be changed unless you know what you're doing
* If you believe something needs to be added to the `Default` tab, please contact the **UUFF Tech Team**

---

### ✅ When You're Ready

1. Click the **📤 Export to JSON** button
2. A new file will be generated and uploaded to Drive automatically
3. A **download link** will appear in cell **D1** of the first sheet
4. The generated `.json` file will be saved to https://drive.google.com/drive/folders/1AjPn10mcKp3G0w68HGMlYEIawjooPdsP as "uuff-obs-overlay_{DDMMYYYY} for the **UUFF Tech Team** to import into the UUFF OBS Overlay control panel.

---

### 🔍 Validation (Optional but Recommended)

You can also click the **✔️ Validate Data** button to check:

* That no keys are missing
* That there are no duplicate entries across sheets
* That everything is ready for export

---

### 📞 Need Help?

If you're unsure how to fill out a section or see unexpected behavior, please reach out to the **UUFF Tech Team** for assistance.
