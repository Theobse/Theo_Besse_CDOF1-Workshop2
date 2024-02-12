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
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/1f533d34-9efc-40a3-a7c0-d51660569d56)

# IPFS

**Q1 - Upload the previous image to IPFS.**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmeJaufp9seXCpHMFwxX53P3oRQW8Ny1DduCXAxebEwxv7
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/4038f0ed-86fe-4b0d-be27-361758121278)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/cbdb24ff-31ad-45f9-b279-516bd6e2de0f)

**Q2 - Now upload partition1 to IPFS. What do you observe compared to the torrent part?**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmPKRGW6BQ3i4Z4W4etVogYDRqoJRyFRCcD5FJrPKgNJPK
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/a85664f1-9561-4b34-b813-5aba05844800)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/6830ccc9-c00b-4e5e-bf44-f5a82c771a66)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/22eda215-60b4-4178-9326-75aa23d044e9)

**Q3 - Copy the partition1 folder and then generate the associated torrent. What do you observe?**

Après avoir importé l'image sur IPFS, on obtient le CID suivant : QmPKRGW6BQ3i4Z4W4etVogYDRqoJRyFRCcD5FJrPKgNJPK
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/1f1c4056-74f8-4985-8583-5c4a2a598a22)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/f9dcdcc0-99d4-41d6-ac18-2be5a1f13715)
![image](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/40d74624-c5f2-47a3-96c1-93c842755158)

## Upload files on IPFS using Pinata

On utilise le code javascript "pinata.js" afin d'importer des fichiers sur IPFS en utilisant Pinata grace à la clé qu'on a créé précédement sur Pinate.
![Sans titre](https://github.com/Theobse/Theo_Besse_CDOF1-Workshop2/assets/116637028/debee51b-9cb6-4757-9a39-1f4620c9617d)

