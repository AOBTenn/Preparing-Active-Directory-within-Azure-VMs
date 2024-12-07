# Preparing Active Directory Environment Within Microsoft Azure Virtual Machine
![image](https://github.com/user-attachments/assets/e4f41676-9505-49cf-82a1-c1ad2d5cf390)



This is an outline of the steps needed to be completed before installing Active Directory. Basically you will be setting up the environment within Microsofth Azure with two virtual machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Virtual Machines
- Internet 

<h2>List of Prerequisites</h2>

- Laptop or Desktop Pc                                                                                                                                 
- Wifi Access
- MKicrosoft Azure Account

<h2>Procedure Steps</h2>

![image](https://github.com/user-attachments/assets/8ecf164a-2440-4a74-a6e5-7b3def1f659d)
<p>Image 1
</p>

![image](https://github.com/user-attachments/assets/01838b92-b0e2-4f62-b11d-a4d30f1d9c5a)
<p>Image 2
</p>

![image](https://github.com/user-attachments/assets/a49416d7-6bdb-4f56-bce0-f765f35de347)
<p>Image 3
</p>

![image](https://github.com/user-attachments/assets/4658e411-7320-4460-b52d-30efefb3aa88)
<p>Image 4
</p>

After logining into or creating a Microsoft Azure account you will be on the home screen. In the search bar type Resource Group (RG) and click on that option to go to the Resource Group page. On this page in the top left corner click the creatre button to create a Resource Group an  be taken to the create a (RG) page. On the create a Resource Group page type the name of your (RG) in the tab, then select a region to save the data in. Next press the review+create button and then the create button to actually have the Resource Group made.

![image](https://github.com/user-attachments/assets/2ba22787-26cb-48ed-866b-38b8d36c8f2f)
<p>Image 5
</p>

![image](https://github.com/user-attachments/assets/a63ef035-f213-4c96-8100-0aa29ace084f)

<p>Image 6
</p>

Next you create the Virtual Network. In the search bar type Virtual Network (VN) and click that option to go to the VN's home page. On the home page in the top left corner click the create button to go to the Create a Virtual Network page. On this page type the name of you (VN), and place the Virtual Network under the previously made Resource Group and in the same region as the resource group. Next click the review+create button and then the create buttton.

![image](https://github.com/user-attachments/assets/c25ee35e-f0e8-4bc2-bd2b-3c060223b336)
![image](https://github.com/user-attachments/assets/fbb1f3c1-da0a-4e45-8888-cf60cc66ddb0)
![image](https://github.com/user-attachments/assets/b1bb605b-ca39-4f8b-9058-25cd1a491f8c)
![image](https://github.com/user-attachments/assets/617fcfb8-0f56-43c3-8625-02197298af42)
![image](https://github.com/user-attachments/assets/409804be-1833-4b0e-9349-b76e91098b05)
![image](https://github.com/user-attachments/assets/ba43c57b-885f-4ac7-a240-415cbb77a9b8)
![image](https://github.com/user-attachments/assets/fbf282c3-0a51-46ef-9ef4-52c13c33cf9c)



Next we create the two Virtual Machines, for demonstration purposes "Dc-1" and "Client-1". Dc-1 is going to be a server while Client-1 is going to be a Windows operating Virtual Machine (VM). To create a (VM) go to the search bar and type Virtual Machines and click on that option to go the the (VM) home page. On this home page  in the top left corner click create and choose "Azure Virtual Machine" option from the drop down menu to go to the create a (VM) page. On create a virtual machine page name it "DC-1", then place it in same region and resource group. Next set security type to standard, pick the "Windows Server 2022" image, set the user name and password, and check the license box, then click the disk tab at the bottom. Next click the network tab and on the network tab make sure the (VM) is put in the Virtual Network created in previous steps. Lastly press review+create and then create.

![image](https://github.com/user-attachments/assets/c25ee35e-f0e8-4bc2-bd2b-3c060223b336)
![image](https://github.com/user-attachments/assets/70bef57e-05ea-4060-af75-585dd2752b81)
![image](https://github.com/user-attachments/assets/00de40b2-97f2-465b-9c83-48f1e6e790da)
![image](https://github.com/user-attachments/assets/da8a5033-f132-466a-a8b1-7fe85d613c85)
![image](https://github.com/user-attachments/assets/f97a9803-c6e5-4bfd-8181-159d5d1ef35f)
![image](https://github.com/user-attachments/assets/c207c679-838c-40b4-9630-7acf98040629)
![image](https://github.com/user-attachments/assets/aa35a7f7-76fa-4d6e-8da7-d0cda847e8cd)




Now create "Client-1" Virtual Machine. To create a (VM) go to the search bar and type Virtual Machines and click on that option to go the the (VM) home page. On this home page  in the top left corner click create and choose "Azure Virtual Machine" option from the drop down menu to go to the create a (VM) page. On create a virtual machine page name it "Client-1", then place it in same region and resource group. Next set security type to standard, pick the "Windows 10 Pro, version 22H2" image, set the user name and password, and check the license box, then click the disk tab at the bottom. Next click the network tab and on the network tab make sure the (VM) is put in the Virtual Network created in previous steps. Lastly press review+create and then create.


![image](https://github.com/user-attachments/assets/2ea9ac3a-5f9a-4ad1-95c8-a57b5965c215)


On this new repository page, first you name the repository by clickng and typing under the Repository Name box. 
  Second you decide if you want the repository page to be public or private.
  Third you can choose if you want o add readme file, .gitignore., and the license.


![image](https://github.com/user-attachments/assets/fca92535-0058-454c-9761-cdaac486d652)

<p>Image 5
</p>

![image](https://github.com/user-attachments/assets/fc151d57-5615-4cba-abfa-42a68cf720b2)

<p>Image 6
</p>

The type of license you want the material in and the repository to be restricted under (ref. image 5). For a better understanding  on the different license option click on this link:
  https://choosealicense.com/ (ref. image 6). 


![image](https://github.com/user-attachments/assets/47bb07cf-5173-4653-a0a0-9b63c310538f)

<p>Image 7
</p>

![image](https://github.com/user-attachments/assets/cc551a57-1f0c-4dfd-8a19-3d3c1f5455d3)

<p>Image 8
</p>

Then you click the green "Create Repository" button to create the repository (ref. image 7). You will be taken to the new repository page after it is made (ref. image 8).
