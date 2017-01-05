# insertion-sort-alg
public static void insertion_sort(int[] a, int n) {
for (int i = 1 ; i < n; i++) {
for (int j = i; j > 0; j--) {
if (a[j] <a[j - 1]) {
int tmp = a[j];
a[j] = a[j - 1];
a[j - 1] = tmp;
} else {
break;
}
}
}
}
