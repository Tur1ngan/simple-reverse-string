#include <iostream>
using namespace std;

string reverse(string w, int i, int j)
{
    if(i > j)
    {
        return "";
    }
    else
    {
        return w[j - 1] + reverse(w, i, j - 1);
    }
}

int main()
{
    string W;
    int I, J;
    
    while(cin >> W >> I >> J)
    {
        cout << W.substr(0, I - 1) + reverse(W, I, J) + W.substr(J) << endl; 
    }
    
}
