# Blank-VDMK-file-for-VMware-Cosmos
A blank fat32 .vdmk file for Vmware with CosmosOS

## To Use:

### Step 1:

Create a folder (wherever) and paste the .vdmk file and your CosmosOS generated .iso file.

### Step 2:

Create a new virtual machine with the .iso like you normally would.

### Step 3:

Open "Edit Virtual Machine Settings"

### Step 4:

![image](https://user-images.githubusercontent.com/100168416/182986998-d2f91af1-8506-44f8-a74e-67f3f7b65761.png)

Select the "Hard Disk (IDE)" option, and at the bottom of the window click "Remove"

### Step 5:

![image](https://user-images.githubusercontent.com/100168416/182987182-52083c44-d263-4b85-aad1-552ea00b5a45.png)

Click the "Add" button next to the "Remove" button at the bottom of the window. Select "Hard Disk" in the "Add Hardware Wizard" box.

### Step 6:

Click Next. Select the "IDE (Recommended)" option. Click Next.

![image](https://user-images.githubusercontent.com/100168416/182987400-86c0c885-0ba2-4ae9-9e78-0adf5ff46c74.png)

Select "Use an Existing Virtual Disk". Click Next.

### Step 7:

Locate your downloaded .vdmk file.

![image](https://user-images.githubusercontent.com/100168416/182987627-8ed1eb1e-7da3-4494-8e28-cd0d34c1f56a.png)

Click Finish. You can now boot your Cosmos OS .iso file on VMWare. Cheers!
