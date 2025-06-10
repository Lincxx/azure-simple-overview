# azure-simple-overview
---
In this lab we are going to make sure we understand some basics about Azure. 

---

1. Create a Resource Group
2. Create a Storage Account within the Resource Group created in Step 1
3. Create a text file on your local desktop If you’re using a Mac, go to preferences and set it to plain text.
4. Upload the text file you created to the Azure Storage Account.
5. Edit the file within the Storage Account (within the Azure Portal)
6. Download the file
7. Open the file and observe the changes
8. Delete the Resource Group created in step 4 (in order to ensure you don’t incur “cost”)
9. Verify that the Resource Group has been deleted

---

**It the top search bar we are going to type in rescource groups and then click on the matching result (resource grouops)**
![Screenshot_20250610_165024](https://github.com/user-attachments/assets/f51aa1df-c2da-4fac-9b11-b33836e03773)
![Screenshot_20250610_165124](https://github.com/user-attachments/assets/1dd1b3a3-2be3-4aab-a15e-45b6127ccaf3)

**Click on create** 
![Screenshot_20250610_165318](https://github.com/user-attachments/assets/7d38685b-a4fd-428b-8dc6-969304bb83c2)

**Then you will see this screen**
![Screenshot_20250610_165414](https://github.com/user-attachments/assets/ed61ff1b-4444-43cc-a373-7a9e34452ab3)

**The Resource group name - we are going to make this unique. Something like 'RG-Azure-Basic-Overview'
As you can see it auto selected the 'Subscription' and 'Region'. You can edit as you please.**
![Screenshot_20250610_165554](https://github.com/user-attachments/assets/6a3c6bae-44ea-48c7-887f-0c3e334a8f36)

**Press 'Next'. Here we are presented with tags a key value pair. We don't need to fill this out at this moment, but I went ahead and did it.**
![Screenshot_20250610_165832](https://github.com/user-attachments/assets/62c5b7f1-9beb-4a88-a2b5-ae8bb5cf20d2)

**From here we are gonna press 'Review & create'. Then click on the bottom button**
![Screenshot_20250610_170010](https://github.com/user-attachments/assets/f38b2787-c140-416e-a1e1-c04db81e4a00)

**You will be presented with screen. Then press create on the bottom of the page**
![Screenshot_20250610_170221](https://github.com/user-attachments/assets/7ac7914a-2083-4dc5-9714-09c037ce7209)

**You will be brought back to the 'Resource group' screen. I like to press F5 to refresh the page and see if the new resource group has been created**
![Screenshot_20250610_170433](https://github.com/user-attachments/assets/ef4bd33a-43c4-45b8-b082-62dbe53a74b1)

**New create a local file. I went with test.txt and entered in the text of Hello**

**Nest to we need to add a 'Stogage account' to our resource groups. This is what we are gonna use to upload, eidt and download our file**
![Screenshot_20250610_170714](https://github.com/user-attachments/assets/6c4ddde7-3be5-40b4-8a5e-fb36ee8ea893)

**After you clicked in the 'Storage accounts' from the search results. Go ahead and click on the 'create' button**
![Screenshot_20250610_170904](https://github.com/user-attachments/assets/cdb5e336-4945-44ea-87aa-342992d9d46a)

**This fill in a name for the 'Storage account'. I went with azurebasicov. We are gonna skip the rest of the steps and go straight to 'Review + Create'**
![Screenshot_20250610_171209](https://github.com/user-attachments/assets/c7a5909c-02e0-4354-b159-11aea6df73fc)

**I didn't grab a screeen shot of the next screen, but it bascally is an overview of the new storage. This can take a while, just be patient**

**One it's created. I like to go to the main 'Home' page.**

**From there you should see your 'Resource groups'. Go ahead and click on it**
![Screenshot_20250610_171629](https://github.com/user-attachments/assets/1e4b5298-33cc-41f4-8b47-e90bbcfd4abd)

**As you can see here, the 'Storage account' has been created and is ready to be used**
![Screenshot_20250610_171657](https://github.com/user-attachments/assets/2c73b66b-6cf4-416e-ba76-a41938db8b7a)

**We need to create a 'container' for the 'Storage account'. This you can think of it as a folder...basically**
**Now click on the "Storage account" on the left side you'll see a 'Data Storage' drop down. Click on it and select the 'Containers'**
![Screenshot_20250610_172158](https://github.com/user-attachments/assets/c9f097d6-589c-4884-8993-a0414f18a427)

**Click on the '+ Cotainer' and enter in a name. I went with test and as you can see the new folder has been created. Click on the new folder**
![Screenshot_20250610_172319](https://github.com/user-attachments/assets/73f0ec9b-af82-46bc-91da-abcfedd59f24)

**From here we are going to upload our file. So go ahead and click on upload and select your file. Once completed you should see your newly uploaded file**
![Screenshot_20250610_172512](https://github.com/user-attachments/assets/91b2dfc4-9711-48f7-a5d1-f6179636ca56)

**Next step is to edit the and download the file to see if our changes did indeed take. Right on the file and select 'View/edit'. Type in anything you would like. I went with updated. click save and press download**
![Screenshot_20250610_172746](https://github.com/user-attachments/assets/b78c554b-2d25-4473-8eb0-9f39657a958c)

**Now clean up. I'm going to press the 'Home' link in the upper left hand corner. Then click on the 'Resource groups' we made**
![Screenshot_20250610_172940](https://github.com/user-attachments/assets/aced72bb-9c9b-43ff-a084-07a5f4f14fae)

**Now click on Delete resource group. This will delete everything we made. Again this will take some time.**
![Screenshot_20250610_173052](https://github.com/user-attachments/assets/60365928-9ef0-460b-8254-ca45bf61bb97)

**You will be presented with a confirmation box. Just copy the name of the 'resource group' and entered it into the input field at the bottom and press delete**
![Screenshot_20250610_173144](https://github.com/user-attachments/assets/34cbe068-c737-4406-85c5-84c990a4085c)





