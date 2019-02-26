# For Desktop users to manage large files

## Where to Download the pre-built BMD Orion binaries
If you don't want to build them from source, you can download our pre-built versions with the following IPFS Hashes in the URLs. We are hosting them for you to download from the same BMD Orion app. You have an option to go through our Web app site to access and download them as an example (which will require BMD Utility tokens to access), or simply just download them directly from here. The Web app site is jsut an eaxmple how you can host and serve your own codesets via the BMD Orion app.
Simply click on the link according to your Operating System and the download will proceed.

* [Mac OSX](https://cloudflare-ipfs.com/ipfs/QmXkhuQ3U3QsYo9nDVBHwZUvG35cv6Ytnn35P4bLxF7E2u/Orion-BlockMed-0.9.1.dmg)

## How to Use it
The following example demonstrates how you can use the Mac OSX version of the BMD Orion app to register your codeset and host them at the same time from the BMD Orion app.

1. Download the binaries from above for your desktop accordingly. Double click to unzip it. You should see the following **Orion-BlockMed.app** in your folder. Double click on it.

![Step 0](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step0_ui.png)

2. You should see the following screen shows up. This presents the basic UI of the BMD Orion App and there are 2 default files listed which is provided by default from the IPFS. Now, there is one IPFS running on your desktop while BMD Orion App is running.

![Step 1](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step1_ui.png)

3. Now, click on the **+** on the top left menu bar to select a file to upload. Here, we are going to add all of the BMD Orion App binary from the above as an example to upload all of them to our local IPFS that is running on your desktop at the moment. We host and register our own BMD Orion App the same way as you can host your file as well. 

![Step 2](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step2_ui.png)

Since we are uploading more than 1 file here, it will ask you if you would like to bundle them into 1 directory, or seperate them into 5 files. We choose **No** here to seperate them into individual files. **Note**: If you want to bundle a set of dataset or codeset together, you will want to select **Yes** here if you want to provide all of them in one batch for users to download.
![Step 3](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step3_ui.png)

Now, you should see all 5 files added to your local IPFS and highlighted at the moment in our BMD Orion App.
![Step 4](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step4_ui.png)

4. Now, select the file you would like to register with BlockMed. Here, we pick the first one which is the Windows binary of our BMD Orion App. Right click and select **Register Code on BlockMed**.

![Step 5](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step5_ui.png)

5. A window will pop up on your browser. **Chrome** is required since you will be using Metamask. Make sure you enter some descriptions. The better you describe the files, the easier others can find them. The keywords you put in here are also serachable and will be indexed by BlockMed indexing engine powered by Elastic Search.

![Step 6](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step6_ui.png)

6. Once you register, and confirm in Metamask, you will see your file listed under the https://ipfs.blockmed.me/file-access page.

![Step 7](https://github.com/BlockMedical/BMD-distributed_hosting_projects/blob/master/BMD-OrionUsage/step7_ui.png)

Now, your are ready. Whenever an user access your code set, the rewards will be forwarded to your wallet.

## Importing Large Files?
If you want to download large files after accessing them, the best practice is not to use the browser to download them since browsers are not designed to download large objects and directories at once. In order to do so, you will want to use the **Menu Bar** => **File** => **Import from hash**. For a real example, you can take a look over [here](https://github.com/BlockMedical/BMD-deep_learning_projects#training-data-and-applying-machine-learning-and-ai-algorithms).
