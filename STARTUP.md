# Designing a Data Product with the Semarchy VS Code extension

Welcome to your new design workspace. It contains everything you need to begin designing and deploying data products for the Semarchy Data Platform.

---

## Workspace structure

A typical Semarchy design workspace includes the following folders:

```
/workspace			# VS Code workspace
└── /data-product-package
    ├── /src		# Source files for design-time objects
    └── /resources  # Non-code assets, such as payloads or images

```

- Use the `src` folder for all your design content.
- Use the `resources` folder for configuration files and supporting assets.

---

## Quick start

Follow these steps to prepare your workspace and start designing your data product.

### 1. Authenticate to the Semarchy Data Platform

1. Configure the Instance Url setting here [link to semarchy.dm.instanceUrl setting] and point to your Data Platform instance, in the format https://<tenant-url>.
2. Select the Semarchy view, then click Login in the Authentication section.
3. Your browser opens to the Data Platform sign-in page. Follow the instructions to complete authentication, then return to VS Code.

After a successful login, the Authentication section in the Semarchy view displays your identity and authentication status.

### 2. Create your data product model

1. Right-click the **src** folder.
2. Select **Semarchy > Create Data Product Model**.
3. Enter a data product name and confirm.

Your workspace now contains a base data product that you can begin editing.

### 3. Configure the extension

1. Open the **Extension Settings** (⚙️ icon in the Extensions view).
2. Under the **Workspace** tab, set the following properties:
   - **Datasource**: Target datasource name
   - **Data Location**: Target data location name

---

## Next steps

You’re ready to start designing!

- Explore the [Semarchy Data Platform documentation](https://docs.semarchy.com/sdp/) for modeling concepts, deployment guidance, and CLI usage.
- Visit the [Semarchy support site](https://www.semarchy.com/support/) for assistance.

---

© Semarchy. All rights reserved.
