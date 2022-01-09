# Grupi2_Gr26_InternetSecurity_Projekti3
Zhvillimi i aplikacionit që mundëson enkriptimin me AES


# Ideja mbrapa kodit 

![image](https://user-images.githubusercontent.com/75323781/148647397-e5b30a67-0f26-444b-af4b-b1aa62b9d922.png)

Kodi i implemntuar në gjuhën programuese Python enkripton plaintext me çelësin AES me mundësi zgjedhje prej 3 opcioneve:
   1. 128bit
   2. 192bit
   3. 256bit
 
Në momentin që ju keni zgjedhur një nga opcionet dhe shtypni butonin Enkripto atëhere më posht do të shfaqet plaintext i dhënë nga user dhe po ai tekst i enkriptuar.Gjithashtu janë trajtuar edhe mesazhet e gabimeve në rastin kur forma për dhënien e plaintext do të jetë bosh do të shfaqet mesazhi si vijon "Mesazhi është bosh!".

Për ta bëre funksional kodin duhet t'a importojmë AES nga libraria Crypto.Cipher, të cilën e kemi shkarkuar përmes command line duke përdorur komandën 𝒑𝒊𝒑 𝒊𝒏𝒔𝒕𝒂𝒍𝒍 𝑪𝒓𝒚𝒑𝒕𝒐. "Pip" është package manager për Python. Pra, është tool që na lejon të instalojmë dhe menaxhojmë librari dhe varësi shtesë që nuk shpërndahen si pjesë e librarisë standarde.
Duke pasur parasysh që kodi jonë është kryesisht Graphic User Interface(GUI) ne kemi përdorur Tkinter Tool, të cilën e kemi instaluar përmes komandës pip install tk në command line. Testimet janë shfaqur në direktoriumin e emërtuar "testimet".

