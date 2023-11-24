# Cryptography-File-Storage-Using-Cloud-
This project suggests a method for storing files securely in the cloud that interfaces with Amazon Web Services' (AWS) S3 cloud storage and uses the AES and RSA algorithms.


## Abstract &  APPROACH 
A key tool for safeguarding sensitive data kept in the cloud is cryptography. This document suggests a method for storing files securely in the cloud that interfaces with Amazon Web Services' (AWS) S3 cloud storage and uses the AES and RSA algorithms. The suggested method uses RSA asymmetric encryption to encrypt the symmetric key and AES symmetric encryption to encrypt the files. The extremely scalable and stable AWS S3 bucket is where the encrypted files and keys are ultimately kept.

## PROPOSED SYSTEM 
The proposed system for Cryptography File Storage Using Cloud would offer a highly secure and reliable storage solution for sensitive data. The system would employ two fundamental encryption algorithms, AES and RSA, to ensure the confidentiality and integrity of the data. The encrypted files and keys would be securely stored in the cloud using Amazon Web Services (AWS) S3 cloud storage, which provides scalability, flexibility, and high availability. To enable authorized users to manage their files, the system would include a frontend application, which would offer a user-friendly interface for uploading, downloading, and managing files securely. 
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

This frontend application would be designed to ensure ease of use for all users, regardless of their technical expertise, while also offering the highest level of security. Additionally, the integration with AWS S3 cloud storage would ensure that the system is cost-effective and reliable, as AWS S3 is a highly scalable and robust storage solution. 

## Block Diagram
![image](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/f8df4505-f45d-43e2-b201-5cf288e0722d)

## Technical Features:
Some of the technical features and elements of the proposed Cryptography File Storage Using Cloud system may include:

1. Encryption Algorithms: The system utilizes the AES and RSA encryption algorithms to ensure secure storage and retrieval of files.
2. Frontend Application: The system includes a frontend application that provides an easy-to-use interface for users to upload, download, and manage their files securely.
3. AWS S3 Cloud Storage: The system integrates with AWS S3 cloud storage, which provides scalable and reliable storage for user files.
4. User Authentication: The system includes user authentication to ensure that only authorized users have access to the files stored in the cloud.
5. Data Backup and Recovery: The system includes data backup and recovery mechanisms to ensure that files are not lost due to system failures or user errors.
6. Secure Data Transfer: This ensures secure data transfer between the user's computer and the cloud storage using SSL/TLS protocols.

## Features/Elements: Frontend
![Frontend](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/16f5a778-be44-41df-b137-02b44b9cf455)

![Frontend](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/afe0ed32-590d-420a-aabb-759db8883077)

##  File Encryption and Decryption
![Fig4. File Encryption and Decryption](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/301d9d25-c438-4c5e-9497-211dff875005)

![File Downloaded.](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/2ba6a72b-17b8-43ec-bc8e-1ba220e4f902)


## Block Diagram
![image](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/df86ddf5-bc5b-45d3-b003-fa318d116a2b)


## Hardware and Software Components used:
The required hardware and software components for the project include:

Hardware:
●	User's computer or device: Used to access the frontend application and upload files.
●	Server: Used to host the backend of the system and store encrypted files in the cloud. The server can be a basic computer with sufficient processing power, memory, and storage capacity.
Software:
●	Programming Languages: Used to implement the system, such as Java, Python, or PHP.
●	Encryption Algorithms: Used to encrypt and decrypt files, such as AES and RSA.
●	Frontend Framework: Used to build the user interface of the system, such as HTML, CSS, and JavaScript.
●	Backend Framework: Used to build the backend of the system, such as Flask or Django.
●	Cloud Storage Provider: Used to store the user's encrypted files in the cloud, such as AWS S3 or Google Cloud Storage.

## Implementation of the work:

![Pycharm Terminal](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/2b6c8d90-e617-4c91-a2ef-260040ed8309)
Command 1:  python main.py -t upload -b pradyumn -i test.png
The command "python main.py -t upload -b pradyumn -i test.png" is used to upload a file named "test.png" to an S3 bucket named "pradyumn". The "-t" flag specifies that the task is to upload a file, while "-b" indicates the name of the S3 bucket. Finally, "-i" specifies the name of the file that needs to be uploaded. 

![Upload Image in S3 bucket](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/d581d229-ab0c-4e7f-8a8c-bdea9de9acc1)
Command 2: python main.py -t decrypt -i testresponse.png
The command "python main.py -t decrypt -i testresponse.png" is used to decrypt a file that has been previously encrypted using the system. 

![Decryption using AES Symmetric Key](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/16e19a3d-fd84-4b38-81fc-306ff576f18b)
Now, open Mailtrap Interface. Mailtrap is a platform designed to assist developers in testing their email notifications securely and in a controlled environment. When Mailtrap is used, the emails generated by the application are not actually sent to real email addresses. Instead, they are caught and saved in an inbox inside the Mailtrap system. This inbox can be accessed by the developer, who can view the email's contents such as the sender, recipient, subject, body, and any attachments. Moreover, Mailtrap offers additional information such as the email headers and IP address, which can be useful in resolving issues related to email delivery.


![Mailtrap Test Mail](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/d07c70cc-e0fb-41a9-a107-f394fd9b8f66)

![The Primary Key and Cipher Key in MailTrap](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/0847d801-d437-4b3e-99fb-38ec17ec32f6)
The primary key consists of two integers (4807 and 36503), which are typically used as part of a public key cryptography system. The cipher key is a list of integers (which appears to be randomly generated) and is used for symmetric key cryptography, where the same key is used for both encryption and decryption. The nonce is a randomly generated value that is used to ensure that each encryption of the same plaintext produces a different ciphertext. 


## AMAZON S3 Bucket:
Amazon S3 bucket is a cloud-based storage service offered by Amazon Web Services (AWS) that allows users to store, manage, and retrieve data from anywhere on the web. It is designed to provide highly scalable, reliable, and durable storage for a wide range of data types, including images, videos, documents, and more. 


![image](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/37f28c46-15e3-4cbf-b65b-b8e130604927)

![image](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/3bbdc148-4a98-4afb-9175-0977703d4f20)

![image](https://github.com/Nishu2903/Cryptography-File-Storage-Using-Cloud-/assets/117971452/108e1400-9b84-45db-8d5a-3032610f7992)























