#include <iostream>

using namespace std;

unsigned long silnia_iter(unsigned int n)
{
    int wynik = 1;
    for(unsigned int i=2; i<=n; i++)
    wynik *= i;
    return wynik;
}

unsigned long silnia_rek(unsigned int n)
{
    if(n>0)
        return n*silnia_rek(n-1);
    else
        return 1;
}

int main()
{

   cout << silnia_iter (28) << endl;
   cout << silnia_rek (28) << endl;


  return 0;
}
