# PROXIDALITY - create your OWN proxy, backed by NightProxy's Space

**PROXIDALITY** lets you host your own proxy using GitHub Codespaces and NightProxy’s Space project. Fast, secure, and customizable.

---

## ⚠️ Important Notice

We do **not** claim ownership of the original codebase. Full credit goes to [NightProxy](https://github.com/NightProxy) and all original contributors of the [Space](https://github.com/NightProxy/space) repository.

This project is purely a personal fork/setup guide intended to help others deploy their own instance using GitHub Codespaces.  
**We do not own or control any part of the original source code.**

Use responsibly and respect all terms and conditions of GitHub, your school network, and the original authors.

---

## ⚙️ Requirements

- A GitHub account
- Browser with JavaScript enabled

---

## 🚀 How to Set Up

1. **Fork the Repository**

   - Go to [https://github.com/NightProxy/space](https://github.com/NightProxy/space) and click the **Fork** button in the top-right corner.
   - Make sure to **uncheck** the option to **only copy the ***main*** branch**.

3. **Create a Codespace**

   - On your forked repo page, click the green **Code** button.
   - Select the **Codespaces** tab.
   - Click **the three dots** and then **"New with options"**.
   - Choose the **4-core processor** option for **MAXIMUM** performance. Otherwise, simply click the **Create codespace** button without tweaking any setting/options.

4. **Start the Proxy**

   Inside your Codespace terminal (once it loads), **right-click and paste** the following commands all at once:

   ```bash
   git clone https://github.com/NightProxy/space.git
   cd Space
   pnpm i
   pnpm start
   ```

5. **Launch the Proxy**

   Once the terminal shows the **Space logo** and a message saying it's ready:
   
   - Click the **"Open in Browser"** button on the notification that will pop-up. If you miss the notification, then click the **PORTS** option , then click the link next to the port.
   - Your proxy is now live!

---

# ⚠️ IMPORTANT
## 💤 When You're Done

To avoid using up your GitHub Codespace hours:

1. Go to your [GitHub Dashboard](https://github.com).
2. Click your **repository name** on the left panel.
3. Click the green **Code** button → **Codespaces**.
4. Click the **three dots** next to your Codespace → **Stop Codespace**.

---

## 🔁 To Restart Later

1. Go back to your forked repo.
2. Open the **Codespace**.
3. Once loaded, type:

   ```bash
   pnpm start
   ```

That’s it — your proxy is back online!

---

## 📜 License and Credit

All code originates from [NightProxy](https://github.com/NightProxy/space).  
We do not take any credit or responsibility for the source project.  
This is **not an official release or fork** — just a quick deployment guide for educational use only.
