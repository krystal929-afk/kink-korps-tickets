# kink-korps-tickets
# Kink Korps: "Anything Goes" Play Party Ticket Template System

This repository hosts the necessary assets and HTML template for generating and distributing digital tickets for Kink Korps events. The goal of this system is to maintain a professional brand experience while scaling the ticket distribution process directly within Gmail.

## 📁 Repository Contents

*   `ticket-template.jpeg`: The definitive, high-resolution flyer image (with event details and metal border). This image is the main visual component of the ticket.
*   `template.html`: The HTML code for the email body.
*   `README.md`: (This file) Documentation and instructions.

---

## 🚀 System Usage: How to Generate a Ticket

This process combines your hosted GitHub image with a stored Gmail Template. Once set up, it takes seconds per guest.

### Initial Setup (Do this once)

#### 1. Host the Image with GitHub Pages
1.  Navigate to your repository's **Settings > Pages**.
2.  Set the Branch source to `main` and save.
3.  Wait for your site to go live. Your image's direct link will be:
    `https://[yourusername].github.io/kink-korps-tickets/flyer_final.png`

#### 2. Configure the HTML Template
1.  Open `template.html` in this repository.
2.  Locate the line that reads:
    `src="REPLACE_THIS_WITH_YOUR_GITHUB_HOSTED_FLYER_IMAGE_URL"`
3.  Replace that exact text with your live image link from Step 1.

#### 3. Save as a Gmail Template
1.  In Gmail, compose a new email. Ensure Plain Text mode is *off*.
2.  Paste the entire contents of your updated `template.html` directly into the email body (this requires inserting it as HTML).
3.  Ensure the flyer image loads correctly.
4.  Remove all placeholder text (e.g., `[START TICKET DATA SECTION]`).
5.  Click the three-dot icon (More Options) near the bottom, select **Templates**, then **Save draft as template** > **Save as new template**.
6.  Name it: `Kink Korps Ticket Template`.

---

### Guest Distribution (Do this for every guest)

1.  Start a new email in Gmail to the guest's address.
2.  Add a clear subject line, e.g., `YOUR TICKET: Anything Goes Play Party - [Date]`.
3.  Select the **Templates** icon (three-dot menu) and load the `Kink Korps Ticket Template`.
4.  In the email body, you will see the full flyer image followed by the editable ticket details.
5.  **Manually replace the placeholders:**
    *   Change `[Your unique ticket number here]` to the generated ticket number.
    *   Change `[Enter Guest Name Here]` to the guest's full name (as it will appear at the door).
6.  *Double-check the details for accuracy.*
7.  **Click Send.**

---

## ⚙️ Maintenance & Updates

*   **Changing Event Details:** To update the event details (date, time, location) shown *on the flyer*, you must generate a new flyer image, upload it to this repository, and ensure the `template.html` link is updated if the filename changes.
*   **Modifying Guest Data:** To change the list of guests or ticket types (e.g., admitting a couple), simply create a new ticket following the distribution steps.

## 🤝 Guest Support & Contacts

For any questions or issues regarding the ticket system, please contact:

*   **System Admin:** [Insert Admin Name/Email Here]
*   **Door Support:** [Insert Door Support Phone/Email Here]
*   **Event Coordinator:** [Insert Event Coordinator Email Here]
