# NGROK RDP-2023
By Imran


![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fadtitas%2Fngrok-rdp%2F&labelColor=%2314213d&countColor=%23e5e5e5&style=flat-square)

## Description
**What is RDP?**<br>
* RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.

## How to use it?

#### First Step
1. Press the **fork** button  
2. Login or signup to ngrok: https://ngrok.com
3. Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
> You'll get token from here. It'll be needed to the next step.

#### Second Step
1. In your forked repo: **Go to Settings > Secrets > Action > New Repository Secret**
2. In the name section, enter this text: **NGROK_AUTH_TOKEN**
3. In the value section, enter the **ngrok token**
4. Then press **Add Secret**
5. Now go to **Action > AWS (Left Menu) > Run Workflow**
6. After building you will see Username & Password
<img src="https://i.imgur.com/uqYO7QB.png" alt="ss" width="60%"/>
7. To get your RDP IP go to https://dashboard.ngrok.com/cloud-edge/endpoints
8. You'll get IP from there.
<img src="https://i.imgur.com/gSpsoyt.png" alt="ss" width="60%"/>

#### Third Step
1. Search **Remote Desktop Connection** from Windows Start Menu and open.
2. Put IP without **tcp://** and enter Username & click **Connect**.
3. Later on, put the password for credential/auth.
<img src="https://i.imgur.com/oDozqcR.png" alt="ss" width="40%"/>

## Screenshots
<img src="https://i.imgur.com/vgD2owk.png" alt="ss" width="90%"/>
<img src="https://i.imgur.com/8XBLUqf.png" alt="ss" width="90%"/>

## License
The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT License](LICENSE.md).
