# -C-programs

[12/08, 9:09 pm] SUBASRI: #include <iostream>
using namespace std;

int main() 
{    
    cout << "Size of char: " << sizeof(char) << " byte" << endl;
    cout << "Size of int: " << sizeof(int) << " bytes" << endl;
    cout << "Size of float: " << sizeof(float) << " bytes" << endl;
    cout << "Size of double: " << sizeof(double) << " bytes" << endl;

    return 0;
}
[12/08, 9:10 pm] SUBASRI: #include <iostream>
 
using namespace std;
 
int main() {
    float a, b, product;
    cout << "Enter two Numbers\n";
    cin >> a >> b;
    product = a*b;
    cout << "Product = " << product;
    return 0;
}
