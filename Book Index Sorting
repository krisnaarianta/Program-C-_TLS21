#include <iostream>
#include <string>
#include <algorithm>
using namespace std;
int main () {
    string name [256];
    int n,i,j,x;
    cout << "Masukkan jumlah buku: ";
    cin >> n;
    cout << "\nMasukkan judul buku: \n";
    for (i=0; i<=n; i++){
        getline(cin, name[i]);}
    sort(name, name + n);
    cout << "\n------ Indeks Buku ------\n";
    x=0;
    for (j=1; j<=n; j++){
        x++;
        cout << x << ". " << name[j]<< "\n";}
}
