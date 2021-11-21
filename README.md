# How-to-Fix-Verification-Error-on-Cypress

How to Fix  "Cypress verification timed out " or " Command timed out after 30000 milliseconds" on Cypress

![image](https://user-images.githubusercontent.com/89155137/142765200-5f26848d-ae51-4052-a13e-ca1b12f12b65.png)

![image](https://user-images.githubusercontent.com/89155137/142765231-ece30528-c621-4f74-9638-c291bcbf33bf.png)

2 solutions is here. You can try both of them

First solution :

![image](https://user-images.githubusercontent.com/89155137/142765370-84ad7aff-f4d3-4fe0-bdc9-2c8e4353958b.png)

![image](https://user-images.githubusercontent.com/89155137/142766021-c60e0bad-ecd1-4a79-8d5e-7a493d950459.png)

Second solution :

![image](https://user-images.githubusercontent.com/89155137/142765414-a55184ba-554e-4db9-a2f6-5c45d5044c4c.png)

![image](https://user-images.githubusercontent.com/89155137/142765974-136f2151-0c46-4dda-83bd-e7d46f1d2e21.png)

Pictures of steps for second solution :

You will click "node_modules" folder

![image](https://user-images.githubusercontent.com/89155137/142765524-9ee360e9-541f-4521-af25-4c59acb7319e.png)

Then, you will click "cypess" folder

![image](https://user-images.githubusercontent.com/89155137/142765604-bcc790ac-a859-4828-a505-342ad1ba5122.png)

Then, you will click "lib" folder

![image](https://user-images.githubusercontent.com/89155137/142765627-883b2937-1829-43e6-b9d0-5d842e4e7224.png)

Then, you will click "task" folder

![image](https://user-images.githubusercontent.com/89155137/142765659-61ea5fe6-21c9-42e4-a80c-a520d2c04bbe.png)

Then, you will click "verify.js" file

![image](https://user-images.githubusercontent.com/89155137/142765679-885eb756-9019-42f1-805d-f2bf21816a30.png)

Then, you will find "VERIFY_TEST_RUNNER_TIMEOUT_MS" line

![image](https://user-images.githubusercontent.com/89155137/142765782-690821a5-0ce0-424c-ba76-80854875a76b.png)

Default value should be 30000

![image](https://user-images.githubusercontent.com/89155137/142765941-4ebe8d57-3ad0-46f8-8539-ad81f7e772b9.png)

Change it to 100000

![image](https://user-images.githubusercontent.com/89155137/142765827-c87a0345-6f82-42e2-85be-3405ab5add08.png)

Finished :)
