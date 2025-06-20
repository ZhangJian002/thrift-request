## License

This plugin is **not open-source**. It is a commercial plugin licensed via JetBrains Marketplace. All rights reserved.

## 🧩 Plugin Dependency

This plugin depends on another free plugin developed by the author: **Thrift Assistant**.  
You do **not** need to install it manually — it will be installed automatically when you install **Thrift Request**.

> ⚠️ Note: Thrift Assistant is based on **Thrift Support**. To avoid compatibility issues, please remove any other plugins based on Thrift Support before using this plugin.

---

## 🚀 Getting Started

### 1. Configure Projects & Environments

Before sending requests, please add your **project** and **environment** information.  
The plugin uses your environment configuration to manage requests uniformly.  
> The request prefix should follow the format: `ip:port` (e.g., `127.0.0.1:9090`)

<img src="./addEnv.gif" />

---

### 2. Generate Parameters from Thrift Methods

Once your environment is set up, open any **`.thrift` file** and locate a method under a `service`.

Each method will have a **rocket icon 🚀** next to it.  
Clicking it will automatically generate a corresponding request in the **Thrift Request** panel.

- The plugin will extract parameter names and generate editable placeholders.
- You may modify the values, but **do not change the parameter names**.
- The parameter format must strictly follow the defined structure.

---

### 3. Send the Request

Click the **"Send"** button in the Thrift Request panel.  
The plugin will:

- Automatically invoke the target server method
- Display the **return value** and key metadata in the response panel
- Support switching between different **response tabs** to view raw result, status, and logs

<img src="./request.gif" />


