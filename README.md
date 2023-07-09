# sample C++ Template
```cpp
#include <bits/stdc++.h>
using namespace std;
#define MASK(i) (1LL << (i))
#define BIT(x, i) (((x) >> (i)) & 1)
#define Times cerr << "time: " << clock() / 1000.0 << endl
#define fi first
#define base 31
#define sz(x) (int)(x).size()
#define se second
#define ll long long
#define mp make_pair
#define pb push_back
#define pii pair<int, int>
#define all(x) (x).begin(), (x).end()
#define task "test"

const int INF = 1e9 + 7;
const ll LINF = (ll)1e18 + 7;
const int MOD = 1e9 + 7;
const int MOD2 = 1e9 + 696969;
const int N = 3e5 + 3;
const int BASE = 10;

template <typename T1, typename T2>
bool minimize(T1 &a, T2 b)
{
    if (a > b)
    {
        a = b;
        return true;
    }
    return false;
}
template <typename T1, typename T2>
bool maximize(T1 &a, T2 b)
{
    if (a < b)
    {
        a = b;
        return true;
    }
    return false;
}

int n, k;

void Solve()
{

}

void file()
{
    if (fopen(task ".inp", "r"))
    {
        freopen(task ".inp", "r", stdin);
        freopen(task ".bug", "w", stderr);
        freopen(task ".out", "w", stdout);
    }
}

int main()
{
    ios_base::sync_with_stdio(0);
    cin.tie(0);
    // file();
    int T = 1;
    // cin >> T;
    while (T--)
        Solve();
    return 0;
}
```
