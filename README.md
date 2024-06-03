# Strongest-neighbour
Find the strongest neighbor i.e print the highest adjacent of two adjacent numbers in an array
//Print the highest adj number of 2 adj numbers(Strongest Neigbour) 
#include<iostream>
using namespace std;

int main(){
	int n;
	cout<<"Enter size of array: ";
	cin>>n;
	int arr[n];
	for(int i=0;i<n;i++){
		cin>>arr[i];
	}
	for(int j=1;j<n;j++){
		if(arr[j-1]>arr[j]){
			cout<<arr[j-1]<<" ";
		}
		else{
			cout<<arr[j]<<" ";
		}
	}
	return 0;
}
