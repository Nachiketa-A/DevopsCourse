# Advanced Linux Commands

To create a directory: sudo useradd username -m

To see which users we craete: cat /etc/passwd

<img width="545" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/0e48bf9e-e6cc-412c-8e75-8e179e129280">

To create a group: sudo groupadd groupname

When we create a user by default group is also get created for that user

<img width="524" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/38dcf602-5e31-47d5-b54b-4dfa13195512">

To see which groups are present or created: cat /etc/group

<img width="339" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/a51c9ad5-9250-4ef8-b90b-f31bed40d74d">

To add user in a group: sudo usermod -aG groupname username

<img width="405" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/a788ed59-58c1-49e6-b68f-0824b8187467">

### Username got added to a group devops

<img width="155" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/8b0f1425-320c-4257-a066-44da464dec94">


To add multiple users in a single group: sudo gpasswd -M username1,username2 groupname **(Here -M overwrites the user)**

<img width="469" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/148025e5-04f6-4db0-a379-be6e53790637">
<img width="294" alt="image" src="https://github.com/Nachiketa-A/DevopsCourse/assets/157089767/351d6a3e-07e5-4af8-864d-5de2c35336a8">
















