<div align="center">
  
  <br />
  <br />

  <h2 align="center">TSP - website</h2>

  Tourest is fully responsive travel website, <br />Responsive for all devices, built using HTML, CSS, and JavaScript.

  <a href="https://codewithsadee.github.io/tourest/"><strong>➥ Live Demo</strong></a>

</div>

<br />

### Demo Screeshots

![Tourest Desktop Demo](./readme-images/desktop.png "Desktop Demo")

### Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

### Run Locally

To run **Tourest** locally, run this command on your git bash:

Linux and macOS:

```bash
sudo git clone https://github.com/Rahi88/TSP.git
```

Windows:

```bash
git clone https://github.com/Rahi88/TSP.git
```
Of course! Here’s the **complete, polished guide in one block**, ready to copy-paste into your README or anywhere you need:

---

````markdown
## 🚀 How to Deploy the Static Website on AWS EC2

1️⃣ **Launch an EC2 instance (Ubuntu recommended)**  
- During setup, make sure your EC2 security group has an inbound rule to allow **TCP port 80 (HTTP)** open to 0.0.0.0/0.

2️⃣ **Connect to your EC2 instance** using SSH:
```bash
ssh -i /path/to/your-key.pem ubuntu@your-ec2-public-ip
````

3️⃣ **Update your package lists:**

```bash
sudo apt update
```

4️⃣ **Install Apache2 web server:**

```bash
sudo apt install apache2 -y
```

5️⃣ **Move to the Apache web root directory:**

```bash
cd /var/www/html
```

6️⃣ **(Optional) Remove the default Apache index page:**

```bash
sudo rm index.html
```

7️⃣ **Clone your project repository into the web root:**

```bash
sudo git clone https://github.com/yourusername/your-repo.git .
```

8️⃣ **Restart Apache to apply the new website:**

```bash
sudo systemctl restart apache2
```

9️⃣ **Access your website** by visiting:

```
http://your-ec2-public-ip
```


![Screenshot (269)](https://github.com/user-attachments/assets/22db434f-de0f-4433-b003-05583e0153f9)

### License

This project is **free to use** and does not contains any license.
