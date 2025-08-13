#include <iostream>
using namespace std;
int main(){
    int r1,c1,r2,c2;
    cout<<"Enter number of rows of 1st matrix: ";
    cin>>r1;
    cout<<"Enter number of columns of 1st matrix: ";
    cin>>c1;
    cout<<"Enter number of rows of 2nd matrix: ";
    cin>>r2;
    cout<<"Enter number of columns of 2nd matrix: ";
    cin>>c2;
    int m1[50][50],m2[50][50],result[50][50]={0};
    if(c1==r2){
        cout<<"\nEnter elements of First Matrix:\n";
        for(int i=0;i<r1;i++){
            for(int j=0;j<c1;j++){
                cout<<"Element ["<<i<<"]["<<j<<"]: ";
                cin>>m1[i][j];
            }
        }
        cout<<"\nEnter elements of Second Matrix:\n";
        for(int i=0;i<r2;i++){
            for(int j=0;j<c2;j++){
                cout<<"Element ["<<i<<"]["<<j<<"]: ";
                cin>>m2[i][j];
            }
        }
        for(int i=0;i<r1;i++){
            for(int j=0;j<c2;j++){
                result[i][j]=0;
                for(int k=0;k<c1;k++){
                    result[i][j]+=m1[i][k]*m2[k][j];
                }
            }
        }
        cout<<"\nProduct of matrices:\n";
        for(int i=0;i<r1;i++){
            for(int j=0;j<c2;j++){
                cout<<result[i][j]<<" ";
            }
            cout<<endl;
        }
    } else {
        cout<<"Matrix multiplication not possible";
    }
    return 0;
}
/*Output:-
Enter number of rows of 1st matrix: 3
Enter number of columns of 1st matrix: 3
Enter number of rows of 2nd matrix: 3
Enter number of columns of 2nd matrix: 3

Enter elements of First Matrix:
Element [0][0]: 1
Element [0][1]: 2
Element [0][2]: 3
Element [1][0]: 4
Element [1][1]: 5
Element [1][2]: 6
Element [2][0]: 7
Element [2][1]: 8
Element [2][2]: 9

Enter elements of Second Matrix:
Element [0][0]: 1
Element [0][1]: 2
Element [0][2]: 3
Element [1][0]: 4
Element [1][1]: 5
Element [1][2]: 6
Element [2][0]: 7
Element [2][1]: 8
Element [2][2]: 9

Product of matrices:
30 36 42 
66 81 96 
102 126 150 
*/
