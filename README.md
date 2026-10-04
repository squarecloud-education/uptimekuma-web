# 🔗 Square Uptime Kuma
## Host Uptime Kuma on Square Cloud ☁️

> 🌐 Easily host your own Uptime Kuma instance on Square Cloud and monitor your websites and services from anywhere, right from your browser.

---

## 🚀 How to host this project on Square Cloud

New to Square Cloud? Follow these steps in order. You will create an account, choose a plan and upload a ready-made zip: no coding needed.

### 1️⃣ Create your Square Cloud account

Sign up on the [Square Cloud signup page](https://squarecloud.app/en/signup) with your email.

### 2️⃣ Choose a plan

Hosting on Square Cloud requires an active plan, and the upload in step 4 asks for one, so choose it now.

Uptime Kuma needs **1 GB of RAM**: the **[Hobby plan](https://squarecloud.app/en/pricing)** runs it. To monitor many services, the **[Standard plan](https://squarecloud.app/en/pricing)** gives it more RAM and CPU. Compare every plan and its price on the [pricing page](https://squarecloud.app/en/pricing).

### 3️⃣ Download the project

Download **`project.zip`** from the [latest release](https://github.com/squarecloud-education/uptimekuma-web/releases/latest). This is the file you upload in the next step: you don't need to extract it.

### 4️⃣ Upload it to Square Cloud

1. Open the [Square Cloud upload page](https://squarecloud.app/en/dashboard/new).
2. Select the **zip** option and send the `project.zip` you downloaded.
3. Select **Web Publication** and choose a subdomain, for example `my-uptime-kuma`. Your Uptime Kuma will be at `https://my-uptime-kuma.squareweb.app`.
4. Click **Deploy**.

![Uploading a project to Square Cloud](https://cdn.squarecloud.app/docs/articles/dashboard/uploading.gif)

There is no port to configure: Uptime Kuma reads the `PORT` and `HOST` variables that Square Cloud sets.

### 5️⃣ Create your admin account

Open `https://my-uptime-kuma.squareweb.app`. If it asks which database to use, choose **SQLite**. Then create your admin account: the first person to open the page creates it, so do it before sharing the URL with anyone.

📖 Need more details? Read the [full Uptime Kuma guide](https://docs.squarecloud.app/en/tutorials/how-to-deploy-uptime-kuma) in the Square Cloud documentation.

---

## 📚 About the project

The goal of this project is to let you host an Uptime Kuma instance on Square Cloud, so you can monitor your websites and services from anywhere, directly from your browser.

---

🙋‍♂️ **Questions or suggestions?** Contact [Square Cloud Support](https://squarecloud.app/sac) or open an issue in this repository!

---

## 🙏 Credits

Maintained by [@JoaoOtavioS](https://github.com/JoaoOtavioS) on GitHub.
