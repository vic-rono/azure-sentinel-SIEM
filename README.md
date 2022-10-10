# azure-sentinel-SIEM

SIEM for getting attackers IP address and their geolocation and using that data to plot a map for monitoring.

The project is a basis for identifying and defending against attacks from persistent threat actors.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 1. Configuring the honey-pot Windows 10 virtual machine

![honey-pot vm](https://user-images.githubusercontent.com/61822296/194932594-a96defe9-e502-4414-ac64-3dbf9368e6fe.png)<br>

## 2. Creating a log analytics workspace to monitor logs from the event-viewer from the Windows 10 Virtual Machine

![LOG_ANALYTICS](https://user-images.githubusercontent.com/61822296/194932596-6854866b-e7c7-49f5-88f2-cdefbd4f7691.png)

## 3. Creating a custom log that will extract log details from the windows 10 Virtual Machine

![CR-CUSTOM LOG](https://user-images.githubusercontent.com/61822296/194932612-7f90cb2b-5dfe-463d-bb22-7888debe7667.png)

## 4. Creating custom fields so that microsoft sentinel can analyze and plot a map

![CUSTOM LOGS](https://user-images.githubusercontent.com/61822296/194932616-ee779c9a-3d88-4cca-a44e-d33082f3ca0b.png)

## 5. Running the powershell script that generates logs and shows attacks.

![Screenshot (9)](https://user-images.githubusercontent.com/61822296/194932601-726138c6-c366-40ed-82c6-55a7b787561d.png)

## 5. The map showing attacks from the world. Here showing the latitude and number of attacks from various countries

![FINAL MAP](https://user-images.githubusercontent.com/61822296/194932576-d623092d-7d71-46e3-b51c-e9e2a6decb16.png)
