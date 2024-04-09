# Penumbra-Seremoni
İşletim Sistemi: Ubuntu 22.04+

    sudo apt update
    sudo apt install screen
    
  - PCLI YUKLEME
    ```
    curl -sSfL -O https://github.com/penumbra-zone/penumbra/releases/download/v0.71.0/pcli-x86_64-unknown-linux-gnu.tar.xz
    unxz pcli-x86_64-unknown-linux-gnu.tar.xz
    tar -xf pcli-x86_64-unknown-linux-gnu.tar
    sudo mv pcli-x86_64-unknown-linux-gnu/pcli /usr/local/bin/
    pcli --version
    #Burda hata vermemesi gerekir.
    ```
    ```
    pcli init soft-kms generate
    #SEED kelimeleri yedekleyin. 
    ```
       
    ```
    pcli view address 0
    #Çıkan adresi kopyalayın.
    ```
    [Burdan discorda katılıp #testnet-faucet kanalından test tokeni talep edin.](https://discord.gg/hKvkrqa3zC).
    
    ```
    pcli view sync
    #Senkronize edelim.
    ```
    ```
    pcli view balance
    #Bakiye kontrol edelim. 100 token gelecek.
    ```
     ```
    screen -S pen
    pcli ceremony contribute --phase 1 --bid 60penumbra --coordinator-address penumbra1qvqr8cvqyf4pwrl6svw9kj8eypf3fuunrcs83m30zxh57y2ytk94gygmtq5k82cjdq9y3mlaa3fwctwpdjr6fxnwuzrsy4ezm0u2tqpzw0sed82shzcr42sju55en26mavjnw4
    #hata vermeden slot ve uzun bir numara verecek vermezse elimizde token ne kadar kalırsa onunla deneyelim. kalmazsa 0 olarak deneyelim. bağlanması uzun sürüyor. ctrl+a+d ile çıkış yapıp ara ara kontrol edebiliriz. hata verirse hemen veriyor zaten. 
    ```
    Sosyal medyada paylaşım yaptıktan sonra. Formu dolduralım.
    [Tıklayın](https://form.asana.com/?k=kWyyWPzQMkJoNTmrfAbWaA&d=1206052071402903)
    
    [Burdan kontrol edebilirsiniz cüzdan adresini](https://summoning.penumbra.zone/phase/1)

    # Seremoni Faz 2
    ```
    screen -S pen2
    ```
    ```
    pcli ceremony contribute --phase 2 --bid 60penumbra
    ```
     Sosyal medyada paylaşım yaptıktan sonra. Formu dolduralım.
    [Tıklayın](https://form.asana.com/?k=THhk7qmp3IDwCvXWTPHkow&d=1206052071402903)

    [Burdan kontrol edebilirsiniz cüzdan adresini](https://summoning.penumbra.zone/phase/2)
    
          
