#include <iostream>
using namespace std;
int main(){
    int r,c;
    cout<<"Enter number of rows: ";
    cin>>r;
    cout<<"Enter number of columns: ";
    cin>>c;
    int m[50][50], t[50][50];
    cout<<"Enter elements of matrix:\n";
    for(int i=0;i<r;i++){
        for(int j=0;j<c;j++){
            cout<<"Element ["<<i<<"]["<<j<<"]: ";
            cin>>m[i][j];
        }
    }
    for(int i=0;i<r;i++){
        for(int j=0;j<c;j++){
            t[j][i] = m[i][j];
        }
    }
    cout<<"Transpose of matrix:\n";
    for(int i=0;i<c;i++){
        for(int j=0;j<r;j++){
            cout<<t[i][j]<<" ";
        }
        cout<<endl;
    }
    return 0;
}
/*Output:-
Enter number of rows: 3
Enter number of columns: 3

Enter elements of matrix:
Element [0][0]: 1
Element [0][1]: 2
Element [0][2]: 3
Element [1][0]: 4
Element [1][1]: 5
Element [1][2]: 6
Element [2][0]: 7
Element [2][1]: 8
Element [2][2]: 9

Transpose of matrix:
1 4 7 
2 5 8 
3 6 9 
*/
