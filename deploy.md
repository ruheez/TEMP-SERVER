## Getting Started

- Fork the Repo

First, you'll need to fork this repository to your GitHub account. You can do this by clicking the [Fork](https://github.com/kavidu-dilhara/Kali-Linux-VPS/fork)
 button at the top right corner of this page.
![fork](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/0.jpg)


- Start a New Project on raliway

Next, sign up for an account on [raliway.app](https://railway.app/dashboard) and create a new project.

![Create a new project on raliway](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/1.jpg)

Choose "GitHub" as the deployment option and select the forked repository.

![Choose GitHub as the deployment option and select the forked repository](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/3.jpg)

- Add Variables

Once your project is set up, go to the "Variables" section and add two variables:

- `NGROK_TOKEN`: This is your [ngrok](https://dashboard.ngrok.com/get-started/your-authtoken) authentication token.
- `Password`: This is the password you want to set for the Kali Linux VPS.

![Add variables in raliway](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/7.jpg)
![Add variables in raliway](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/8.jpg)

- Find the Endpoint

Locate the Ngrok [endpoint](https://dashboard.ngrok.com/endpoint) you will see like this after copy the Url
![endpoint](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/12.jpg)

- Connect with ssh

`ssh root@0.tcp.ngrok.io -p 19341`
You need to replace your own url and port

### You've successfully installed Kali Linux GUI in Raliway
![Successful](https://github.com/kavidu-dilhara/Kali-Linux-VPS/blob/main/img/14.jpg)

fix sudo error [Issue](https://github.com/kavidu-dilhara/Kali-Linux-VPS/issues/1#issuecomment-1480050821)
