# Splunk Lab-letsdefend.io
-->
Prior: LetsDefend provides a virtual environment to do this lab. I couldn’t connect to lab, so I used a VM I already had by using Windows 11.
1- Use the credentials LetsDefend’s lab provided when you select “Connect Issue.” It will release you details- see below.

Note: Each time you try to connect to the lab, the hostname details changes, FYI.. If Splunk server automatically disconnects, you may need to terminate server and connect again. It will give you a new hostname and have to start from scratch again.
![Screenshot 2025-07-05 125358](https://github.com/user-attachments/assets/7fc31fdb-7384-4c99-b0be-b504dac6005c)

2- Open a browser. Enter the hostname and password as its given.

![Screenshot 2025-07-05 125556](https://github.com/user-attachments/assets/45273f07-a832-43d6-bec3-e32fb7c7d048)


3- Download the data file and upload it to Splunk. You’ll use this data for other questions, don’t skip this part.

4- Go to settings then Add Data

![Screenshot 2025-07-05 125641](https://github.com/user-attachments/assets/e1632793-9186-48bd-8fa1-e9b133bf3872)

5- Click Upload

![Screenshot 2025-07-05 125833](https://github.com/user-attachments/assets/adff5946-b2f2-46a3-9013-aaf05a33c4dd)

6- It will then proceeds to ask questions for configurations.

7- Select the Source type and Host

A source is a file, a network stream, or a specialized output such as a Windows Event Log channel. The Splunk platform uses the “source” field of an indexed event to identify the event’s original location or method of input.

8- Choose what index. You can create your own index to make it easier to search for this particular file to scan
I created my own index so it is easier to view content. Click on “Create a new index.” I named it LetsDefend.

9- Click Review to finalize the configurations
10- Now you can start searching

Questions:

1 How many different client IPs are there requesting the “/productscreen.html” path?
65 is the correct answer.

![Screenshot 2025-07-05 130721](https://github.com/user-attachments/assets/70420366-0159-4ee0-bca6-eca96bd606da)


Question #2:

What is the path where the client IP address “128.241.220.82” sends the most web requests?

/cart.do is the answer.


![Screenshot 2025-07-05 130859](https://github.com/user-attachments/assets/8f5aad17-dc02-427d-81db-e13863b8af11)


Question #3:

How many users do we have on our Splunk?

Search users by going to Settings > Users.
![Screenshot 2025-07-05 131119](https://github.com/user-attachments/assets/03efb141-3deb-402e-9837-2efdf9e4510e)

Answer: It is only 1 user

Question #4:

How many roles do we have on our Splunk?

To find or create a new role, go to Settings > Roles

![Screenshot 2025-07-05 131506](https://github.com/user-attachments/assets/110056c6-5336-421c-bc64-7afb152d478c)

Answer: 5 roles


![Screenshot 2025-07-05 131815](https://github.com/user-attachments/assets/e4df0066-4046-43f8-91f8-96cbae201494)

https://app.letsdefend.io//my-rewards/detail/763fef68-fbb7-44c4-9f5d-39ee011f4fbb









