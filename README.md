<p align="center">
  <img src="assets/icon.png" alt="Power Automate Editor icon" width="80">
</p>

# Power Automate Editor

**Edit your Power Automate flows like code.**

Inspect, edit, validate and publish Microsoft Power Automate flow JSON directly from the designer, with a code editor powered by Monaco.

[**Install from the Chrome Web Store**](https://chromewebstore.google.com/detail/mfdmecomnlocbddniidddpkkomhmpkgl?hl=en) · [Report a bug](https://github.com/MaximeGrn/power-automate-editor/issues/new?template=bug_report.md) · [Suggest a feature](https://github.com/MaximeGrn/power-automate-editor/issues/new?template=feature_request.md)

![Edit a Power Automate flow as JSON alongside the visual designer](assets/edit-flow.png)

## Why use it?

When the visual designer gets in the way, work directly with your flow's JSON without the export, unzip, edit and reimport cycle.

- **Edit in context:** open the JSON editor alongside the Power Automate designer, resize it or move it to a separate tab.
- **Work with a code editor:** syntax highlighting, formatting and JSON schema diagnostics powered by Monaco.
- **Validate before publishing:** run Power Automate validation and review errors and warnings inside the editor.
- **Save or publish:** save changes as a draft or publish the updated flow from the editor.
- **Use your preferred AI assistant:** manually copy JSON into ChatGPT, Claude, Copilot or another assistant to help explain or improve a flow. You choose what to share; there is no built-in AI connection.

## Get started

1. [Install the extension from the Chrome Web Store](https://chromewebstore.google.com/detail/mfdmecomnlocbddniidddpkkomhmpkgl?hl=en).
2. Open a cloud flow in the [Power Automate designer](https://make.powerautomate.com/) and wait for it to finish loading.
3. Click **Editor** in the designer toolbar (tooltip: **Edit the flow as JSON**).
4. Edit the JSON, then click **Validate** to review errors and warnings.
5. Choose **Save draft** or **Publish** when your changes are ready.

You need a signed-in Microsoft account with permission to edit the flow. The extension uses your existing Power Automate session and does not bypass Microsoft permissions or licensing.

Keep a backup before making substantial changes. Validation helps detect issues, but test the flow after publishing to confirm its behavior.

## See it in action

### Validate your changes

![Power Automate validation errors and warnings shown inside the JSON editor](assets/validate-flow.png)

### Save a draft or publish

![Save changes as a draft or publish from the Power Automate JSON editor](assets/save-publish.png)

## Privacy and permissions

Flow editing uses requests from your browser to Microsoft services; it does not require an external editing server. Monaco and JSON schemas are bundled with the extension.

The extension uses browser storage for preferences and session state, tab access for the editor workspace, and access to Power Automate, Power Platform and Dataverse domains to load, validate and save flows using your existing session.

On uninstall, the extension opens a Tally feedback form with technical context in its URL: operating system, extension version, interface language, extension language and installation date. This is separate from flow editing.

If you copy JSON into an AI assistant or attach it to an issue, review it first and remove credentials, personal data and confidential business information.

## FAQ

**Is this repository the extension source code?**

This is the public documentation and feedback repository. The extension source code is not published here. Install the packaged extension from the Chrome Web Store.

**Does it work with Power Automate Desktop?**

This extension is for cloud flows in the browser-based Power Automate designer.

**Where is the editor button?**

Check that the extension is enabled in its popup, refresh Power Automate and wait for the flow designer to load. If it still does not appear, report a bug with your browser version and the steps to reproduce it.

**Can I use it with AI?**

Yes: copy the JSON into your preferred assistant, review its suggestions, then apply and validate the changes in the editor. No AI account or API key is needed by the extension itself.

**What about Microsoft Edge?**

The installation link here is for Chrome. An Edge Add-ons listing will be linked here when available.

## Feedback and support

Found a problem? [Report a bug](https://github.com/MaximeGrn/power-automate-editor/issues/new?template=bug_report.md) with reproduction steps, expected behavior and your browser and extension versions. Screenshots are welcome; remove sensitive details first.

Have an idea? [Suggest a feature](https://github.com/MaximeGrn/power-automate-editor/issues/new?template=feature_request.md) and describe the problem it would solve.

If the extension helps you, a [Chrome Web Store review](https://chromewebstore.google.com/detail/mfdmecomnlocbddniidddpkkomhmpkgl?hl=en) or a GitHub star helps others discover it.

---

Power Automate Editor is an independent project and is not affiliated with or endorsed by Microsoft. Microsoft Power Automate and other product names belong to their respective owners.
