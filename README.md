# Cold War — Official Discord Assets & Embeds

![Main Banner](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/MAIN.png)

Official repository for the **Cold War** Discord server graphic assets and JSON embed configurations. This repository stores permanent image links (`raw.githubusercontent.com`) and message templates for server information channels.

---

## Repository Structure

The repository is divided into default embeds (located in the root directory), seasonal themes (inside dedicated folders), and graphic files:

```text
coldwar-images/
├── assets/                           # Graphic banners & renders
│   ├── christmas/                    # Winter/Christmas themed banners
│   ├── halloween/                    # Halloween themed banners
│   ├── tutorial/                     # Guide screenshots
│   ├── GET-ROLES.png                 # Default Get Roles banner
│   ├── LINKS.png                     # Default Links banner
│   ├── MAIN.png                      # Default Footer render
│   ├── ROLES GUIDE.png               # Default Roles Guide banner
│   └── RULES.png                     # Default Rules banner
│
├── christmas/                        # Christmas themed JSON embeds
│   ├── christmas-get-roles.json
│   ├── christmas-links.json
│   ├── christmas-roles-guide.json
│   └── christmas-rules.json
│
├── halloween/                        # Halloween themed JSON embeds
│   ├── halloween-get-roles.json
│   ├── halloween-links.json
│   ├── halloween-roles-guide.json
│   └── halloween-rules.json
│
├── get-roles.json                    # Default JSON for #get-roles
├── links.json                        # Default JSON for #links
├── roles-guide.json                  # Default JSON for #roles-guide
└── rules.json                        # Default JSON for #rules
```

* **Root `.json` files (outside folders):** Standard everyday embeds used for normal server operation.
* **Folder `.json` files (`christmas/`, `halloween/`):** Thematic embeds pre-configured with seasonal banners.

---

## Embed Generator Tutorial

All server embeds are managed via **[Embed Generator (message.style)](https://message.style/app/editor)**. Follow the steps below to load a JSON file from GitHub and post or edit a message in Discord.

### 1. Open the JSON Editor
1. Open the desired `.json` file in this repository (from the root for standard embeds, or inside `halloween/` / `christmas/` for seasonal ones) and copy its raw code.
2. Go to **[https://message.style/app/editor](https://message.style/app/editor)**.
3. Click the **`JSON`** button (pointed out by the arrow below) to open the code window.

![Open JSON Editor](https://raw.githubusercontent.com/sermalus/coldwar-images/refs/heads/main/assets/tutorial/json_tutorial.png)

---

### 2. Paste the JSON Code & Save
1. Clear any existing code inside the pop-up window.
2. Paste the JSON code copied from GitHub into the text field.
3. Click the **`Save`** button to load the template into the editor.

![Paste JSON and Save](https://raw.githubusercontent.com/sermalus/coldwar-images/refs/heads/main/assets/tutorial/json_editor_save_tutorial.png)

---

### 3. Send a New Embed or Edit an Existing Message
Once the preview loads, use the controls highlighted in the screenshot below:

* **Send a new message:** Select the target channel and click the **Send** button.
* **Edit an existing message:** To update an already posted Discord message without deleting it (for example, switching from Default to Halloween themes), copy the **Message ID** from Discord, paste it into the dedicated ID field, and click **Edit Message**.

![Send or Edit Message](https://raw.githubusercontent.com/sermalus/coldwar-images/refs/heads/main/assets/tutorial/edit_message_send_message_tutorial.png)

---

## Theme Previews

| Default | Halloween | Christmas |
| :---: | :---: | :---: |
| ![Default Rules](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/RULES.png) | ![Halloween Rules](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/halloween/halloween-rules.png) | ![Christmas Rules](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/christmas/christmas-rules.png) |
| ![Default Main](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/MAIN.png) | ![Halloween Main](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/halloween/halloween-main.png) | ![Christmas Main](https://raw.githubusercontent.com/sermalus/coldwar-images/main/assets/christmas/christmas-main.png) |

---

## Credits & License

* **Graphic Design & Layout:** `@sermalus`
* **3D Renders:** `@me3r_dev`

**Copyright © 2026. All Rights Reserved.**  
All graphic assets, renders, and designs in this repository are exclusive intellectual property. Unauthorized copying, modification, or redistribution is strictly prohibited.
