# huu
hjb


#include <iostream>
#include <conio.h>

using namespace std;
int main()

{
    int no,jum,uang,tot,kem,maaf,kurang,kemba;
    char waktu[10],nama[30];

   do {
          
          cout<<"======================================"<<endl;
          cout<<"          ~ Bioskop Beika ~           "<<endl;
          cout<<"======================================"<<endl;
          cout<<" Daftar Film "<<endl;
          cout<<"--------------------------------------"<<endl;
          cout<<"1. Your Name                         "<<endl;
          cout<<"2. Silent Voice "<<endl;
          cout<<"3. Hello World "<<endl<<endl;
          cout<<"Masukkan film yang dipilih [1,2,3] = "; cin>>no;
          cout<<endl;

          if (no==1)
          {
             
              cout<<"====================================="<<endl;
              cout<<"           ~ Your Name ~             "<<endl;
              cout<<"====================================="<<endl<<endl;
              cout<<"Harga Per Tiket            : Rp. 30000"<<endl;
              cout<<"Masukkan Nama Pelanggan    : "; cin>>nama;
              cout<<"Waktu Tayang [Pagi, Siang] : "; cin>>waktu;
              cout<<"Jumlah Pembelian Tiket     : "; cin>>jum;
              tot=30000*jum;
             cout<<"Harga Total Pembayaran   : Rp. "<<tot<<endl;
             cout<<"Uang Yang Dibayarkan     : Rp. "; cin>>uang;
          if (uang<tot)
          {
              cout<<endl;
              maaf=tot-uang;
              cout<<"Maaf Uang Anda Kurang Lagi Rp. "<<maaf<<endl;
              cout<<"Masukkan Kekurangan anda : Rp. "; cin>>kurang;
              kemba=(uang+kurang)-tot;
              cout<<"==================================="<<endl;
              cout<<"Uang Kembalian Anda      : Rp. "<<kemba<<endl;
              cout<<"==================================="<<endl;
          }
          else
          {
           kem=uang-tot;
          cout<<"===================================="<<endl;
          cout<<"Uang Kembalian Anda      : Rp. "<<kem<<endl;
          cout<<"===================================="<<endl;
          }
          }

         if (no==2)
          {
              
              cout<<"====================================="<<endl;
              cout<<"         ~ Silent Voice~             "<<endl;
              cout<<"====================================="<<endl<<endl;
              cout<<"Harga Per Tiket                  : Rp. 25000"<<endl;
              cout<<"Masukkan Nama Pelanggan          : "; cin>>nama;
              cout<<"Waktu Tayang [Pagi, Sore, Malam] : "; cin>>waktu;
              cout<<"Jumlah Pembelian Tiket           : "; cin>>jum;
              tot=25000*jum;
             cout<<"Harga Total Pembayaran   : Rp. "<<tot<<endl;
             cout<<"Uang Yang Dibayarkan     : Rp. "; cin>>uang;
          if (uang<tot)
          {
              cout<<endl;
              maaf=tot-uang;
              cout<<"Maaf Uang Anda Kurang Lagi Rp. "<<maaf<<endl;
              cout<<"Masukkan Kekurangan anda : Rp. "; cin>>kurang;
              kemba=(uang+kurang)-tot;
              cout<<"==================================="<<endl;
              cout<<"Uang Kembalian Anda      : Rp. "<<kemba;
              cout<<endl;
              cout<<"==================================="<<endl;
          }
          else
          {
           kem=uang-tot;
          cout<<"===================================="<<endl;
          cout<<"Uang Kembalian Anda      : Rp. "<<kem<<endl;
          cout<<"===================================="<<endl;
          }
          }
          
          if (no==3)
          {
             
              cout<<"====================================="<<endl;
              cout<<"         ~ Hello World ~             "<<endl;
              cout<<"====================================="<<endl<<endl;
              cout<<"Harga Per Tiket              : Rp. 20000"<<endl;
              cout<<"Masukkan Nama Pelanggan      : "; cin>>nama;
              cout<<"Jadwal Tayang [Siang, Malam] : "; cin>>waktu;
              cout<<"Jumlah Pembelian Tiket       : "; cin>>jum;
              tot=20000*jum;
             cout<<"Harga Total Pembayaran   : Rp. "<<tot<<endl;
             cout<<"Uang Yang Dibayarkan     : Rp. "; cin>>uang;
          if (uang<tot)
          {
              cout<<endl;
              maaf=tot-uang;
              cout<<"Maaf Uang Anda Kurang Lagi Rp. "<<maaf<<endl;
              cout<<"Masukkan Kekurangan anda : Rp. "; cin>>kurang;
              kemba=(uang+kurang)-tot;
              cout<<"==================================="<<endl;
              cout<<"Uang Kembalian Anda      : Rp. "<<kemba<<endl;
              cout<<"==================================="<<endl;
          }
          else
          {
           kem=uang-tot;
          cout<<"===================================="<<endl;
          cout<<"Uang Kembalian Anda      : Rp. "<<kem<<endl;
          cout<<"===================================="<<endl;
          }
          }

          cout<<endl<<endl;
          cout<<"== SELAMAT MENONTON =="<<endl<<endl;

      }

   
   cout<<endl<<endl;
   cout<<" == Terima Kasih == "<<endl<<endl;

}
