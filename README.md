# Docker-Learning
Here’s a beginner-friendly **README file** that you can use as a study guide and personal documentation while learning Docker from **Abhishek Vermala's Docker playlist**. It covers the basics like virtualization, hypervisor, containers, and Docker lifecycle in simple language.

---

# 📦 Docker Learning Notes – Abhishek Vermala Playlist

> By: Sarvesh Ghankhede
> 📚 Beginner-friendly Docker notes for quick revision & easy understanding

---

## 🧠 What is Virtualization?

* **Virtualization** is the process of running multiple operating systems on a single physical machine.
* It allows you to **create virtual machines (VMs)** using software called a **hypervisor**.

### Types of Virtualization:

1. **Full Virtualization** – Each OS runs separately with its own kernel.
2. **Paravirtualization** – OS knows it’s running in a virtual environment.

---

## 💻 What is a Hypervisor?

* A **hypervisor** is software that creates and manages virtual machines.

### Types:

* **Type 1 (Bare Metal)** – Directly installed on hardware
  *e.g., VMware ESXi, Microsoft Hyper-V*
* **Type 2 (Hosted)** – Installed on a host OS
  *e.g., VirtualBox, VMware Workstation*

---

## 🧱 What is a Container?

* A **container** is a lightweight alternative to a virtual machine.
* It **shares the host OS kernel**, but runs apps in **isolated environments**.
* **Faster & more efficient** than VMs.

> 🟢 Imagine a container as a portable box that has everything needed to run your application.

---

## 🐳 What is Docker?

* Docker is a **platform to build, run, and manage containers**.
* It uses **containerization** to help you deploy your app quickly and efficiently.

---

## 🔄 Docker Lifecycle Explained

1. **Write Dockerfile**
   👉 Define app environment and commands.

2. **Build Image**

   ```bash
   docker build -t myapp .
   ```

   👉 Converts Dockerfile to a container image.

3. **Run Container**

   ```bash
   docker run myapp
   ```

   👉 Runs your app in an isolated environment.

4. **Stop Container**

   ```bash
   docker stop <container_id>
   ```

5. **Remove Container**

   ```bash
   docker rm <container_id>
   ```

6. **Remove Image**

   ```bash
   docker rmi myapp
   ```

> 🔁 You can repeat this cycle every time you make a change.

---

## 🧩 Key Docker Commands

| Command                     | Description                      |
| --------------------------- | -------------------------------- |
| `docker ps`                 | See running containers           |
| `docker ps -a`              | See all containers (stopped too) |
| `docker images`             | List all Docker images           |
| `docker pull <image>`       | Download image from DockerHub    |
| `docker exec -it <id> bash` | Access running container shell   |
| `docker logs <id>`          | View container logs              |

---

## 📌 Why Use Docker?

✅ Lightweight
✅ Fast Startup
✅ Easy to Deploy
✅ Works on "any" machine
✅ Version-controlled app environments

---

## 🎯 My Progress

* [x] Understood Virtualization
* [x] Understood Hypervisors
* [x] Learned about Containers
* [x] Understood Docker Lifecycle
* [ ] Practicing Docker commands
* [ ] Building my own Dockerfile

---

## 🛠️ Next Steps

* Learn how to create custom Dockerfiles
* Work with Docker Compose
* Push images to DockerHub
* Learn real project-based Docker setups

---

Let me know if you’d like this exported to a `.md` file or want me to add Docker Compose, networking, or volumes next!
