#include <AX12A.h> //Kullandığımız Kütüphane

#define DirectionPin (10u) //Kontrol Ettiğimiz Pin Girişi
#define BaudRate (1000000ul) // Dynamixel Servolara Özel Olan Frekans
#define ID (1u) // Servonuz İçin Belirlenen id

void setup() {

delay(1000); //1 saniye bekleme komutu
ax12a.begin(BaudRate, DirectionPin, &Serial); //Servoyu tanımladığımız kısım
ax12a.setEndless(ID,ON); // Sonsuz Dönme Modu Aktif
ax12a.turn(ID,LEFT,100); // Sol tarafa doğru 100 hızında dönüş yap
}

void loop() {

}
