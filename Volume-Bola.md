#include <iostream>
using namespace std;

int main()
{
    printf("Nama : Dzikri Ahmad Maulid\n");
    printf("NPM  : 197006023\n");
    printf("Kelompok : 4\n");
    printf("=============================================\n");
	  float volume,r,pi=3.14;
    cout<<"Program menghitung Volume bangun ruang Bola"<<endl;
    cout<<"Masukkan Jari-jari Bola : ";
    cin>>r;
    volume=pi*r*r*r*4/3;
    cout<<endl<<"Volume Bola = "<<volume<<" cm"<<endl;
    return 0;
}
