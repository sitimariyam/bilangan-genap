# bilangan-genap



    #include <iostream>
    #include <conio.h>
    using namespace std;
    int main() {
    int a=0,b,c,jumlah=0,i,n;
 
    cout<<"MENGHITUNG JUMLAH DERET BILANGAN\n";
    cout<<"Masukan bilangan awal:  ";
    cin>>a;
    cout<<"masukan beda:";
    cin>>b;
    cout<<"masukan jumlah sampai deret ke-n: ";
    cin>>n;
    cout<<"Deret ke-"<<n<<":";
    cout<<a<<",";
    jumlah= jumlah + a;

    for (i=0; i<n-i;i++)
    {   c=a+b;
     a=c;
    cout<<c<<",";
    jumlah=jumlah + c;
    }
    cout<<"\njumlah deret ke-" <<n<<";";
    cout<<jumlah;
    getch();
    return 0;
    }





