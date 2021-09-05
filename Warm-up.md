# GrabCON{W4rm_up} (50 pts)
Categoría: Criptografía
## Descripción
Mukesh used to drink and then smoke 5 times a day. He is now suffering form cancer his drink was 64 rupees and 32 rupees cigarette that costs to cheap for him. And he has this much of cancer now.

Author: Offen5ive

**Trae un archivo adjunto (mukesh.txt)**
## Solución
El contenido del archivo es el siguiente:
```
S01ZRENXU1NJVkhGUVZKUkpaRkZNMlNLSTVKVENWU0xLVlZYQVlLVElaTkVVVlRNS0pIRkc2U1dKVkpHV01LWEtaQ1VVVENXTlJORlNVS1dOUkdGS01EVUs1S0dXVlNLS1pDWFFUQ1ROUllFT1VUTE1STFZDTUxFSk5MR1c0Q0lLWVlEQ1RDWEtWMkZNVjJWTkJKRk1SS09MQktHV05EWktKV0U0VlNOTlJTRVdWVEtLSkxWR01CUklOTEdXNUNQS05XRkVSQ1dLWkhFSVVaUk9CTUZFMjJXS1ZKVENXU0tLWlZWVVJTVUdGTEZLVkNGR0ZIVTRSU1ZQRkdXWVRTTUtOVlRLVEtTR0ZSVEFVSlFNUkdGSVZUTUs1SkZNVExaS1pWWElWMk5OTkxFNFZUS0pKTFZJUkxRSlZKR1dNS1RLTVlEU1RDVk5OMkVRVjJXSlpLRk1WTFVKTkpUQ1VTRUtaV0U0VjJTR0JORklVU1dNUkxGTVJMVUpSSldXNkNYS0lZVlVSQ1RHQVlVT1ZDRk1STUU0VktPS0ZKVENTU0VLWldGTVZLUkdGU0U2VkxMTVJNVktNS1dNRktXV09LREtFWUZVVUNWTk4yRVFVWlJPQkdGTVJLT0s1S1RBM0NNS0pWWFFTQ1hLWlNFSVZMTE1SRFZJMjIySlJMR1dUU0hLSVlWVVMyV05OU0ZHVTMySkpGRksyM0VLVklWTVVTVUtSS1hJVDJXR0JORk1WTDJKSk1GRU1DMktOTEVLUlNXS05XRU1VQ1JOTlNFT1ZEMkpGNUZPVkxMR0ZKVEFXU09LWVlVNFJTVEdGWUVJVlJRTlJKRTIyWlZKNUtHV05LR0tWTEZVVkNXTk00VUdVM0xMSkZGSzIzWUtKSldXU1NMS0lZV0dNS1JHRkpFWVZMTEpaTVZLVlNPSlJLVEE1Q1NLNUtWRVZDV0tWSEZNVVJRSVVZRk0yMkdLWkpXVVZTSktaS0RBT0tRS1FZRFNVQ1JIVTZRPT09PQ==S01ZRENXU1NJVkhGUVZKUkpaRkZNMlNLSTVKVENWU0xLVlZYQVlLVElaTkVVVlRNS0pIRkc2U1dKVkpHV01LWEtaQ1VVVENXTlJORlNVS1dOUkdGS01EVUs1S0dXVlNLS1pDWFFUQ1ROUllFT1VUTE1STFZDTUxFSk5MR1c0Q0lLWVlEQ1RDWEtWMkZNVjJWTkJKRk1SS09MQktHV05EWktKV0U0VlNOTlJTRVdWVEtLSkxWR01CUklOTEdXNUNQS05XRkVSQ1dLWkhFSVVaUk9CTUZFMjJXS1ZKVENXU0tLWlZWVVJTVUdGTEZLVkNGR0ZIVTRSU1ZQRkdXWVRTTUtOVlRLVEtTR0ZSVEFVSlFNUkdGSVZUTUs1SkZNVExaS1pWWElWMk5OTkxFNFZUS0pKTFZJUkxRSlZKR1dNS1RLTVlEU1RDVk5OMkVRVjJXSlpLRk1WTFVKTkpUQ1VTRUtaV0U0VjJTR0JORklVU1dNUkxGTVJMVUpSSldXNkNYS0lZVlVSQ1RHQVlVT1ZDRk1STUU0VktPS0ZKVENTU0VLWldGTVZLUkdGU0U2VkxMTVJNVktNS1dNRktXV09LREtFWUZVVUNWTk4yRVFVWlJPQkdGTVJLT0s1S1RBM0NNS0pWWFFTQ1hLWlNFSVZMTE1SRFZJMjIySlJMR1dUU0hLSVlWVVMyV05OU0ZHVTMySkpGRksyM0VLVklWTVVTVUtSS1hJVDJXR0JORk1WTDJKSk1GRU1DMktOTEVLUlNXS05XRU1VQ1JOTlNFT1ZEMkpGNUZPVkxMR0ZKVEFXU09LWVlVNFJTVEdGWUVJVlJRTlJKRTIyWlZKNUtHV05LR0tWTEZVVkNXTk00VUdVM0xMSkZGSzIzWUtKSldXU1NMS0lZV0dNS1JHRkpFWVZMTEpaTVZLVlNPSlJLVEE1Q1NLNUtWRVZDV0tWSEZNVVJRSVVZRk0yMkdLWkpXVVZTSktaS0RBT0tRS1FZRFNVQ1JIVTZRPT09PQ==
```
Para desencriptarlo primero se identifica el tipo de encriptado, por la descripción podemos inferir que se refiere a 2 tipos de encriptado, base64 y base32, por lo que probamos decodificar con base64 y luego con base32:

![image](https://user-images.githubusercontent.com/66751764/132142056-54d95581-d66b-4dfd-a5f1-779f23150b48.png)

Pero parece ser que sigue encriptado, y lo que sucede es que se debe repetir el proceso 5 veces, lo cual también se puede inferir a través de la descripción, para llegar a la flag **GrabCON{dayuum_s0n!}**
