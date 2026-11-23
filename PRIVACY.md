# Tab Vault — Privacy Policy

_Last updated: 23 November 2026_

Tab Vault is a Chrome extension that saves your open windows and tabs so you can restore them later.

## What data Tab Vault handles
When **you** click "Save" (or when the optional auto-save runs every 30 minutes), Tab Vault records the following for each normal (non-incognito) browser window:
- the page address (URL) and title of each tab
- whether each tab was pinned or active, and its tab group (name and colour)
- the window's size, position and state (e.g. maximised)
- the date and time of the save

## Where it is stored
All of this data is stored **only on your own computer**, in Chrome's local extension storage (`chrome.storage.local`) for your Chrome profile.

- Tab Vault does **not** send any data to the developer or to any other server.
- It contains no analytics, tracking, advertising or remote code.
- It does not use Chrome Sync, so saves are not copied to your other devices.
- Data is never sold, shared or transferred to anyone.

The only way data leaves your computer is if you choose to use **Export saves**. This creates a `.json` file on your computer, and you decide what to do with it.

## Website icons
To show each tab's icon, Tab Vault uses Chrome's built-in favicon cache (the `favicon` permission). The icons come from your own browser and are not fetched from Tab Vault's servers, because Tab Vault has none.

## Permissions and why they are needed
| Permission | Why |
|---|---|
| `tabs` | Read the URL and title of your open tabs so they can be saved, and open them again when restoring |
| `tabGroups` | Save and rebuild tab groups (name and colour) |
| `storage`, `unlimitedStorage` | Keep your saves locally on your computer, even if there are many of them |
| `alarms` | Run the optional auto-save every 30 minutes |
| `favicon` | Show website icons next to saved tabs |

## Deleting your data
- You can delete any save from the Tab Vault page.
- Removing the extension from Chrome deletes all of its stored data.

## Contact
Questions about this policy can be raised as an issue on this GitHub repository.
