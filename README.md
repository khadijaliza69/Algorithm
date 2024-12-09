# Algorithm
#include <iostream>
using namespace std;

int main() {
    int arr[] = {10, 20, 30, 40, 50};
    int size = 5;
    int target;

    cout << "Enter the number to search for: ";
    cin >> target;

    for (int i = 0; i < size; i++) {
        if (arr[i] == target) {
            cout << "Element found at index " << i << endl;
            return 0;
        }
    }

    cout << "Element not found in the array" << endl;
    return 0;
}
