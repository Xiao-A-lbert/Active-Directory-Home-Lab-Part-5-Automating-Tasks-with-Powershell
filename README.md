# Active Directory Home Lab Part 5: Automating Tasks with Powershell

<h2>Description</h2>
In this Active Directory Home Lab, I created a create a powershell script to automate the task of creating a new Active Directory User.   
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell CLI</b>
- <b>Visual Code Studio</b>

<h2>Environments Used </h2>

- <b>Windows Server 22</b> 
- <b>Windows 11 Enterprise</b> 
<br />
<br />
First I installed the Active Directory Certificate Services Tool.

![1) download RSAT](https://github.com/user-attachments/assets/c362ff3e-418d-43f6-886c-bfa6aabbecbd)

<br />
<br />
Then I downloaded the Visual Code Studio.

![2)download VSC ](https://github.com/user-attachments/assets/f9143507-bfed-497a-831c-8920f6a802f7)

<br />
<br />
Created new script called "Create-ADUser.ps1".

![3)opened VSC, created new file, installe powershell extension ](https://github.com/user-attachments/assets/8f02dad0-a821-48b4-9471-70c57a539c56)

<br />
<br />
Made a call to New-ADUser to create the AD user.

![4) creating user parameters neatly with backtick ](https://github.com/user-attachments/assets/3f8d8bdb-4d3a-40c4-8121-caf9e7362c07)

<br />
<br />
Fill out the rest of the ADUser cmdlet.

![5) AD User credentials set up](https://github.com/user-attachments/assets/718c686f-531c-4d4b-a0a8-c462ed5ea10d)

<br />
<br />
Ask for user parameters.

![6) created mandatory parameters for user to pass info in](https://github.com/user-attachments/assets/75ef6c69-6a60-4abd-9238-cefd08c3bcaa)

<br />
<br />
This will generate a random 12 letter password and converts from plaintext into a secure password.

![7) generate random password   turn into secure password](https://github.com/user-attachments/assets/72a1b016-ffcb-4c76-b391-73efea77f542)

<br />
<br />
Save and run script.

![8) enter new user credentials as an active directory admin](https://github.com/user-attachments/assets/06df94b0-4b84-4858-beb7-7c9ea8b309bc)
<br />
<br />
