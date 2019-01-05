# C-Program-pengkonversi-basis-bilangan-10-ke-biner

    #include <iostream>
    #include <conio.h>

    using namespace std;
    void binary(int desimal)
    {
    int sisa;
    int hasil;

    if (desimal <=1)
    {
        cout<<desimal;
        return;
    }
    sisa = desimal %2;
    hasil= desimal/2;
    binary(hasil);
    cout<<sisa;
    }
    int main()
    {
      int a;
      cout <<"MASUKKAN BILANGAN YANG AKAN DIKONVERSI = ";
      cin>>a;
      cout<<a<<" DALAM BINER ADALAH = ";
      binary(a);
      cout <<endl;

      return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Program-pengkonversi-basis-bilangan-10-ke-biner/blob/master/C++%20Program%20pengkonversi%20basis%20bilangan%2010%20ke%20biner.png?raw=true)
