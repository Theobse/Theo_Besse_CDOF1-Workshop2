# Torrent

**Q1 - Create a torrent containing this image.**
   ```bash
   torrent create Chaton.jpeg -o Chaton.torrent
   ```

**Q2 - Now copy the image to a new directory named partition1 and create a torrent of this folder. What do you observe?**
   ```bash
   torrent create partition1 -o partition1.torrent
   ```

**Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?**
   ```bash
   torrent create partition1_copy -o partition1_copy.torrent
   ```

On obtient ainsi les 3 fichiers torrent suivant:
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/97495c76-d1ef-4300-bfdf-bf8e8d8ca09d)

# IPFS

**Q1 - Upload the previous image to IPFS.**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmeJaufp9seXCpHMFwxX53P3oRQW8Ny1DduCXAxebEwxv7
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/993ab4e1-a46e-4078-9499-cd8a32f4bf93)
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/8b245002-cc39-4ec9-9f14-17a5504d96f3)

**Q2 - Now upload partition1 to IPFS. What do you observe compared to the torrent part?**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmPKRGW6BQ3i4Z4W4etVogYDRqoJRyFRCcD5FJrPKgNJPK
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/f034e986-dfe2-4f77-9ea7-21f2e6b9132a)
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/c82e0ed8-2e39-4d06-af65-835b76e79963)
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/837c931a-e1c1-4182-bc51-19720d068ea2)

**Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmPKRGW6BQ3i4Z4W4etVogYDRqoJRyFRCcD5FJrPKgNJPK
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/1f1c4056-74f8-4985-8583-5c4a2a598a22)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/f9dcdcc0-99d4-41d6-ac18-2be5a1f13715)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/40d74624-c5f2-47a3-96c1-93c842755158)

## Upload files on IPFS using Pinata

On utilise le code javascript "pinata.js" afin d'importer des fichiers sur IPFS en utilisant Pinata grace à la clé qu'on a créé précédement sur Pinata.

![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/debee51b-9cb6-4757-9a39-1f4620c9617d)

