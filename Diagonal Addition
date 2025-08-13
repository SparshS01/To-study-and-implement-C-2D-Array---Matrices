#include <iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter number of Rows & Column matrix: ";
    cin>>n;
    int m[50][50], sum=0;
    cout<<"\nEnter elements of matrix:\n";
    for(int i=0;i<n;i++){
        for(int j=0;j<n;j++){
            cout<<"Element ["<<i<<"]["<<j<<"]: ";
            cin>>m[i][j];
        }
    }
    for(int i=0;i<n;i++){
        sum += m[i][i];
    }
    cout<<"\nSum of main diagonal elements: "<<sum;
    return 0;
}
/*Output:-
Enter number of Rows & Column matrix: 3

Enter elements of matrix:
Element [0][0]: 1
Element [0][1]: 1
Element [0][2]: 1
Element [1][0]: 1
Element [1][1]: 1
Element [1][2]: 1
Element [2][0]: 1
Element [2][1]: 1
Element [2][2]: 1

Sum of main diagonal elements: 3
*/
