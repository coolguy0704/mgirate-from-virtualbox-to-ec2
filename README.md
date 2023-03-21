## Description
This project provides a step-by-step guide on how to migrate a virtual machine (VM) from VirtualBox to Amazon Elastic Compute Cloud (EC2) by lift-and-shift approach using a combination of tools and services.

The guide covers the following steps:
1. Export the VM from VirtualBox in the OVA format.
2. Upload the OVA file to Amazon Simple Storage Service (S3).
3. Create an Amazon Machine Image (AMI) from the OVA file using the AWS CLI.
4. Launch an EC2 instance from the AMI.

## Installation
To use this project, you need to have the following installed:
- VirtualBox
- AWS Management Colsole Access
- An IAM user with access to S3 and EC2

## Usage
1. Export the VM from VirtualBox in the OVA format.
2. Upload the OVA file to an S3 bucket.
3. Create an AMI from the OVA file using the AWS CLI.
4. Launch an EC2 instance from the AMI.

Detailed instructions for each step can be found in below screenshots.



<img width="947" alt="Snipaste_2023-03-21_14-59-11" src="https://user-images.githubusercontent.com/116753469/226549440-a1bf7d5d-df28-4fbb-822c-5362f28484f8.png">
<img width="960" alt="Snipaste_2023-03-21_15-00-54" src="https://user-images.githubusercontent.com/116753469/226549443-0c53c8ec-0687-4cc8-8aed-12c62c1275ad.png">
<img width="959" alt="Snipaste_2023-03-21_15-02-16" src="https://user-images.githubusercontent.com/116753469/226549448-3897d91f-8ced-46ce-a2c1-84370265b033.png">
<img width="953" alt="Snipaste_2023-03-21_15-05-59" src="https://user-images.githubusercontent.com/116753469/226549453-68c6f232-f1c4-4716-9f64-b2e84d46c01b.png">
<img width="960" alt="Snipaste_2023-03-21_15-07-25" src="https://user-images.githubusercontent.com/116753469/226549455-ede1b653-df09-460f-ad3d-db0d9565e559.png">
<img width="960" alt="Snipaste_2023-03-21_15-07-45" src="https://user-images.githubusercontent.com/116753469/226549458-9edfd563-8721-460e-a3ba-eb9c5ab2ec50.png">
<img width="544" alt="Snipaste_2023-03-21_15-14-21" src="https://user-images.githubusercontent.com/116753469/226549463-8dc4c326-a5de-4cfb-8896-02c51c2f3445.png">
<img width="919" alt="Snipaste_2023-03-21_15-21-12" src="https://user-images.githubusercontent.com/116753469/226549466-addeb37e-3f92-4e0a-adb3-372b9df7b316.png">
<img width="901" alt="Snipaste_2023-03-21_15-37-02" src="https://user-images.githubusercontent.com/116753469/226549469-cc2a01e1-47b8-41bc-a7af-e959ad5dbeb3.png"><img width="879" alt="Snipaste_2023-03-21_15-42-06" src="https://user-images.githubusercontent.com/116753469/226549496-3e09c9c1-899d-485a-8d57-61d83f195f67.png">
<img width="893" alt="Snipaste_2023-03-21_15-42-56" src="https://user-images.githubusercontent.com/116753469/226549500-4e41c3bd-953c-4828-8bff-ccd13b3a3bef.png">
<img width="754" alt="Snipaste_2023-03-21_15-44-17" src="https://user-images.githubusercontent.com/116753469/226549503-81ac114e-434c-410b-877b-a75bb101660f.png"><img width="908" alt="Snipaste_2023-03-21_15-48-50" src="https://user-images.githubusercontent.com/116753469/226549531-cb744f51-f199-4177-91de-294708b45963.png">
<img width="715" alt="Snipaste_2023-03-21_15-52-53" src="https://user-images.githubusercontent.com/116753469/226549535-06948f37-064b-4fa1-96d1-3a0816283a9c.png">
<img width="636" alt="Snipaste_2023-03-21_15-54-41" src="https://user-images.githubusercontent.com/116753469/226549536-0930f9a8-6c87-4fcb-b369-8bdee2daba28.png">
<img width="601" alt="Snipaste_2023-03-21_16-08-31" src="https://user-images.githubusercontent.com/116753469/226549540-d9879aab-9127-4b75-8389-755486d814e5.png">
<img width="916" alt="Snipaste_2023-03-21_16-10-42" src="https://user-images.githubusercontent.com/116753469/226549543-c9d1fb56-aa50-40e8-87c3-9d6099d12433.png">
<img width="731" alt="Snipaste_2023-03-21_16-11-08" src="https://user-images.githubusercontent.com/116753469/226549544-d54b36f7-ee4a-4a15-97e9-715ec1ad72dd.png">
<img width="639" alt="Snipaste_2023-03-21_16-14-44" src="https://user-images.githubusercontent.com/116753469/226549547-4264ef5a-f48b-494f-9c32-78b20278b6a0.png">
<img width="674" alt="Snipaste_2023-03-21_16-16-31" src="https://user-images.githubusercontent.com/116753469/226549552-e8b819f4-8ba0-4b50-be08-fabb0f9149d0.png">
<img width="783" alt="Snipaste_2023-03-21_16-16-46" src="https://user-images.githubusercontent.com/116753469/226549557-45c5adaf-cf3c-4938-8e1b-ba7f81b12520.png">
<img width="785" alt="Snipaste_2023-03-21_16-24-03" src="https://user-images.githubusercontent.com/116753469/226549558-11552881-3aba-4fe9-973c-9a994c3f5fc6.png">
<img width="669" alt="Snipaste_2023-03-21_16-25-05" src="https://user-images.githubusercontent.com/116753469/226549560-5b618fdb-3249-4a0b-a30a-acfc763c0ae7.png">
<img width="399" alt="Snipaste_2023-03-21_16-25-26" src="https://user-images.githubusercontent.com/116753469/226549561-65ef8a23-3474-42c5-88e9-e3e2215ed97e.png">


## Cleanup
At the end delete the S.G, EC2, AMI, Snapshot, S3 objects, S3 bucket, IAM service role as a cleanup.
