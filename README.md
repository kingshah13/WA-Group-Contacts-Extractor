# WA Group Contacts Extractor

A simple Chrome/Chromium extension that extracts contact information from WhatsApp group chats on WhatsApp Web and exports the results to a CSV file.

The included icons are placeholder assets and can be replaced with your own designs.

This extension works with most Chromium-based browsers, including:

- Google Chrome
- Microsoft Edge
- Brave
- Opera
- Vivaldi

---

## Installation

### Option 1: Install from Microsoft Edge Add-ons

Install directly from the Edge Add-ons Store:

👉 https://microsoftedge.microsoft.com/addons/detail/wa-group-contacts-extract/pkopoomjfajbmibjjdcjgmolkikhcfcj

Click **Get** and follow the installation prompts.

---

### Option 2: Load Unpacked Extension

#### Microsoft Edge

1. Open:

   ```
   edge://extensions/
   ```

2. Enable **Developer Mode**.
3. Click **Load Unpacked**.
4. Select the folder containing this repository.
5. The extension is now installed.

#### Google Chrome

1. Open:

   ```
   chrome://extensions/
   ```

2. Enable **Developer Mode**.
3. Click **Load Unpacked**.
4. Select the folder containing this repository.
5. The extension is now installed.

---

## Usage

### Extract Contacts

1. Open WhatsApp Web:

   https://web.whatsapp.com

2. Log in to your WhatsApp account.

3. Open the WhatsApp group from which you want to extract contacts.

4. Click the extension icon in your browser toolbar.

5. Click **Extract Contacts**.

6. A CSV file named:

   ```
   whatsapp_contacts.csv
   ```

   will be downloaded.

---

## Converting Contacts into a Vertical List

The exported CSV contains contact data in a horizontal format. Follow the steps below to transpose the data into a vertical list.

### Microsoft Excel (Windows)

1. Open the exported CSV file.
2. Select **Row 2**.
3. Press:

   ```
   Ctrl + C
   ```

4. Select an empty cell.
5. Press:

   ```
   Alt + H, V, T
   ```

6. Excel will transpose the row into a column.

---

### Microsoft Excel (macOS)

#### Option 1: Menu Path

1. Copy the row (`⌘ + C`).
2. Select the destination cell.
3. Navigate to:

   ```
   Edit → Paste Special → Transpose
   ```

#### Option 2: Right-Click Method

1. Copy the row (`⌘ + C`).
2. Right-click the destination cell.
3. Select **Paste Special**.
4. Enable **Transpose**.
5. Confirm.

#### Option 3: Ribbon Method

1. Copy the row (`⌘ + C`).
2. Select the destination cell.
3. Open the **Home** tab.
4. Click the arrow under **Paste**.
5. Select **Transpose**.

---

## Output

After transposing the data, you will have a clean vertical list of contact numbers that can be imported into:

---
## Known Limitation

> ⚠️ **Current Issue**
>
> The extension currently exports only the first **500 contacts** from a WhatsApp group.
>
> Example:
>
> - Group contains 500 contacts → All contacts export correctly.
> - Group contains 800 contacts → Only the first 500 contacts export while the remaining 300 contacts are not included.
>
> This is a known issue that has not yet been resolved.

Contributions and pull requests are welcome.

---

## Disclaimer

This project was built primarily with the assistance of ChatGPT and other AI tools.

Please use this extension responsibly and always respect the privacy and consent of others when collecting or processing contact information.

---
