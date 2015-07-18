#Enterprise Standards and Best Practices for IT Infrastructure

S.D.W Senanayake 

IT12004850

Log Reports – Lab 1
__________

Date- 	2/7/2015

Task

- Creating an amazon web service account


- Select EC2



- Create one Linux and one windows box
- Linux Box
>SSH/Login
>
>Remote Desktop
>



- Windows Box
>SSH/Login
>
>Remote Desktop

_____

###Creating an Amazon Web Service Account

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a1_zps2bgsmrq7.png)

###After inserting contact details page redirect to the payment information form there user has to have an electronic card to proceed 

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a2_zpsqqbv0wgj.png)

###User can get the contact support as well

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a3_zpssggkuezb.png)

###Confirmation email send to users email

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a4_zps0zvvw9qv.png)

###After user provide the credit card details. The account gets created. User redirected to the logging page there he/she need to enter the user name and the password

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a5_zps7obxyyyu.png)

###Main page opens

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a6_zpsedepvi5y.png)

###Select EC2 Category

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a7_zpsmzqiqciy.png)

###Creating a Linux server

o To create a virtual machine

o Got to the Launch instance button and click it

o	Then the available server types will be appear

>>Free account users can only select the servers, that indicate “Free Tier Eligible”

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a8_zps0ww7h3at.png)



###Select the Operating System (in this case Ubuntu)

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a9_zpss712zpy4.png)

###Follow the process: Configure Instance>Add storage>Tag Instance>Configure Security Group> Review

o	Configure Instance 

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a10_zpsnqdhxbky.png)

o	Add Storage

>>Specifying this size of a root volume may result in the instance not booting successfully. Not all operating systems support root volume that are greater than 2047GiB

>>You can also add new volumes by ‘Add New Volume’ button

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a11_zpsjswejce9.png)

>>Windows volumes cannot be greater than 2048GiB require GPT partition tables

o	Next User can Name the virtual machine

>>Here user can also tag attributes, it helps to track this virtual machine with others

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a12_zpss3pandeq.png)



- Configure Security Group

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a13_zpsch6hghwf.png)


- For security purpose web service offering encryption method, if user already have a key pair he/she can continue with Launch instance if not they can get a new one

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a14_zpszxeqmv2e.png)

- Launch Status will be displayed

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a15_zpst4zkdc9u.png)

o	Click view instance 

>>You can find all your created virtual machines in the grid

>>In order to connect to the Virtual machine Click connect and download remote desktop file

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a16_zps06aj7uqk.png)

>>Use Key file to decrypt password

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a17_zpsd1gysyix.png)

>>Log in to the virtual machine using remote desktop file by using decrypted password(Windows)

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a18_zpsbwpbx4yq.png)

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/a19_zpsqyqkrn4u.png)


- For Linux Virtual Machines

![](http://i288.photobucket.com/albums/ll180/sam_senna/ESBPII%20-Labs/Lab1/linux_zpsiujlmyll.png)


######Logged Modified -4/7/2015

######Logged Modified – 18/7/2015
