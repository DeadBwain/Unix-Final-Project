# Instruction To Customize An ISO Image For Media Industry User
### Step 1: Open your Ubuntu VM and Download original iso image 
Download it from [Ubuntu's official website](https://ubuntu.com/download/desktop)
- Select Ubuntu 21.10

![image](https://user-images.githubusercontent.com/82058058/166126775-a8bbbc04-d8de-4d8b-bac4-3eb44304dc8d.png)

### Step 2: Open terminal and install Cubic
Use the following command:
- $ sudo apt-add-repository ppa:cubic-wizard/release
![image](https://user-images.githubusercontent.com/82058058/166126975-340b1262-c827-406d-84a2-4550251787f7.png)

- $ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys B7579F80E494ED3406A59DF9081525E2B4F1283B
![image](https://user-images.githubusercontent.com/82058058/166126980-a4434585-c44f-4b52-8f68-ce418824bacd.png)

- $ sudo apt update   
![image](https://user-images.githubusercontent.com/82058058/166126989-f6d0f89e-96d6-44be-bf9f-15794478cd90.png)

- $ sudo apt install cubic  
![image](https://user-images.githubusercontent.com/82058058/166126997-bb1016f4-2263-4723-8575-1a4a93243f4f.png)

### Step 3: Open Cubic When It Downloaded Successfully
![image](https://user-images.githubusercontent.com/82058058/166127034-74e520a6-842f-4207-b8d7-fb9bdf21710f.png)

### Step 4: Choose a directory to store the custom iso image
I made a new directory and stored it in **/home/jiamin/project/cubic**     
![image](https://user-images.githubusercontent.com/82058058/166127052-78111a50-962d-4ac5-aa22-9f4b57a48490.png)

### Step 5: Add the original iso image to customize
To add the downloaded original iso image, click the file icon next to the File Name column. All remaining information is automatically filled in.
![image](https://user-images.githubusercontent.com/82058058/166127087-f4742ed1-b323-42ed-95ee-b9d24b2506e0.png)

### Step 6: Loading
It takes a few minutes to create an environment.  
![image](https://user-images.githubusercontent.com/82058058/166127098-5cc96b86-89dd-416e-98ea-c01710b934d6.png)

### Step 7: Enter the virtual environment terminal 
![image](https://user-images.githubusercontent.com/82058058/166127114-57b5cdae-d4e1-43e5-9c0c-a8708030f4bf.png)

### Step 8: Start configuring the desired action 
**Important: Began by adding the universe repository and upgrading downloaded packages to the most recent version!**
Using Command: 
- $ sudo add-apt-repository universe
- $ sudo apt update
![image](https://user-images.githubusercontent.com/82058058/166127148-98dbce61-1be0-40c0-9204-5340199410a4.png)

#### Download media industry-specific software packages.####  
The following website privides a variety of alternatives spcifically for editing:   
[Audio Editing](https://linuxhint.com/audio_editing_music_making_software_linux/)  
[Video Editing](https://itsfoss.com/best-video-editing-software-linux/)  
[Photoshop Alternatives](https://sourcedigit.com/24367-photoshop-alternative-for-ubuntu-linux/)  
[Paint Alternative:](https://www.makeuseof.com/best-paint-alternatives-for-linux/)

I downloaded one in each category
- Gimp (Photoshop alternative): $ apt install gimp 
![image](https://user-images.githubusercontent.com/82058058/166127540-28a44f1d-4b50-4fea-b38c-03fea95748e7.png)

- Audacity (audio editing): $ apt install audacity 
![image](https://user-images.githubusercontent.com/82058058/166127611-322c2fc0-cc98-400c-bd13-74daef551189.png)

- Kdenlive (video editing): $ apt install kdenlive 
![image](https://user-images.githubusercontent.com/82058058/166127614-11b93154-01e4-4e7d-9d73-01bacedcf1ae.png)

- Krita (painting tool): $ apt install krita
![image](https://user-images.githubusercontent.com/82058058/166127620-29d1e27f-ebb4-4baf-b045-19ffc450f9cc.png)

#### Optional: Provide background options ####
**First Part**
1. Change the directory to /usr/share/backgrounds: $ cd /usr/share/backgrounds
2. Download some of the wallpapers available. 
3. Then paste the file from the Downloads folder into the virtual environment's terminal. It will display a new interface like the one below; click Copy.
4. Repeat these procedures for each wallpaper you'd like to use.
![image](https://user-images.githubusercontent.com/82058058/166127667-0d4eff67-0b1f-4f5f-a012-0f2dc1011edc.png) 
![image](https://user-images.githubusercontent.com/82058058/166127676-45fb1382-7d6c-432a-95ce-0cc8eb36d037.png)     
List all the backgrounds in the directory (img19 & outrun-vaporwave are the ones I added): $ ls usr/share/backgrounds  
![image](https://user-images.githubusercontent.com/82058058/166127694-f4dfed1f-0912-4cc6-bfdd-64a20ba393ca.png)

**Second Part**
1. Same as the first part, but in a different directory. Change directory to /usr/share/gnome-background-properties: $ cd /usr/share/gnome-background-properties  
![image](https://user-images.githubusercontent.com/82058058/166127743-1ea5e863-bc6d-4192-8781-bdfc8f40a54d.png)

### Step 9: Choose which packages need to be deleted from the customized iso. 
![image](https://user-images.githubusercontent.com/82058058/166127802-781a3b7d-840a-4385-9951-3a0b2506b925.png)

### Step 10: Select the Kernel
![image](https://user-images.githubusercontent.com/82058058/166127815-b54aec1a-7815-434e-a370-1a72574f86d6.png)

### Step 11: Generate customized iso   
![image](https://user-images.githubusercontent.com/82058058/166127832-06dce1ba-c5e3-4da4-83ba-832e9b76dd21.png)

The following are the details of the custom ISO image that was generated:  
![image](https://user-images.githubusercontent.com/82058058/166127850-383e60b5-6fa2-48d9-b0c5-7eb323e127b5.png)

Check the selected folder to store the customized iso:   
![image](https://user-images.githubusercontent.com/82058058/166127856-4657979e-e7b7-43eb-9257-92fa2ce3246e.png)

### Step 12: Test iso image using Cubic  
![image](https://user-images.githubusercontent.com/82058058/166127896-cb60663c-c552-4c92-a313-334cc9d1871b.png)
  


##
