# 📘 DAY 3

## 🌐 Web Servers, File Permissions and Website Deployment

Today, we learned about Linux file permissions, web servers, and the process of deploying a simple webpage online. We also explored how files are served to users through a web server and how hosting platforms make websites accessible over the internet.

## 🔐 Linux File Permissions

Linux provides a permission system to control who can read, write, or execute a file. Permissions are assigned to three categories of users:

- **Owner:** The user who owns the file.
- **Group:** Users belonging to the file's assigned group.
- **Others:** All other users.

There are three basic permissions:

| Permission | Symbol | Numeric Value |
|---|---|---:|
| Read | `r` | 4 |
| Write | `w` | 2 |
| Execute | `x` | 1 |

### Understanding `chmod`

The `chmod` command is used to change file permissions in Linux.

Examples:

- `chmod 777 filename` — Gives read, write, and execute permissions to the owner, group, and others.
- `chmod 404 filename` — Assigns read permission to the owner, no permissions to the group, and read permission to others. The file must exist for the command to work.

The number `777` represents full permissions for all three categories. However, granting these permissions to every user is generally unsafe and should be avoided unless there is a specific reason.

## 🖥️ Web Servers

A web server receives requests from clients, such as web browsers, and delivers the requested webpages or other resources.

Two popular web servers are:

- **Apache HTTP Server**
- **Nginx**

We also discussed the importance of the `index` file, such as `index.html`, which commonly serves as the default webpage when a visitor opens a website.

## ⚙️ Local Web Development Environments

We were introduced to XAMPP, a development environment used for running web applications locally.

Related environments include:

- **XAMPP:** Commonly used on Windows and other supported platforms.
- **LAMP:** Linux, Apache, MySQL/MariaDB, PHP.
- **MAMP:** A local web development environment commonly associated with macOS.

## 🚀 Deploying a Website Using Vercel

We explored Vercel as a platform for deploying websites and making them accessible through a public URL.

The practical task involved deploying a simple webpage on Vercel and understanding how a project can be published online without managing a traditional physical server.

We also received an introduction to file management and providing access to files through hosting-related tools.

## 💡 Key Learnings

- Understood Linux file permissions and the purpose of `chmod`.
- Learned about owners, groups, and other users in Linux.
- Explored Apache and Nginx as web servers.
- Understood the role of the default index file.
- Learned the basics of local web development environments.
- Gained an introduction to deploying a webpage using Vercel.

## ✅ Conclusion

Day 3 helped me understand how Linux permissions control file access, how web servers deliver webpages, and how a simple website can be deployed online using a hosting platform.
