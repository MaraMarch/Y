#include <iostream>
#include <vector>
using namespace std;
int main() {
    int t;
    cin >> t;
    while (t--) {
        int n;
        cin >> n;
        vector<int> b(n-1);
        for (int i = 0; i < n-1; ++i) {
            cin >> b[i];
        }
        vector<int> a(n, 0);
        a[0] = b[0];
        for (int i = 1; i < n-1; ++i) {
            a[i] = b[i] - b[i-1];
        }
        a[n-1] = b[n-2];
        for (int i = 0; i < n; ++i) {
            cout << a[i] << " ";
        }
        cout << endl;
    }
    return 0;
}





































руша (лат. Pyrus) — род плодовых и декоративных деревьев и кустарников семейства розовые (Rosaceae).
Деревья различного размера, порой крупные кустарники, иногда снабжённые колючками.
