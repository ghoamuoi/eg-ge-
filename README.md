# eg-ge-#include <conio.h>
#include <iostream.h>
#define max 100

void nhap(int[], int);
void sapxep(int[], int);
void xuat(int[], int);

void main()
{
	int a[max], n;
	clrscr();
	cout << "Nhap so phan tu n<" << max << ", n= ";
	{
		cout << "A[" << i + 1 << "]=";
		cin >> a[i];
	}
}

void xuat(int a[], int n)
{
	int i, j;
	for (i = 0; i < n; i++) cout << a[i] << " ";
}

void sapxep(int a[], int n)
{
	int i, j, tg;
	for (i = 0; i < n - 1; i++)
		for (j = i + 1; j < n; j++)
			if (a[i] > a[j])
			{
				tg = a[i];
				a[i] = a[j];
				a[j] = tg;
			}
}#include <conio.h>
#include <iostream.h>
#define max 100

void nhap(int[], int);
void sapxep(int[], int);
void xuat(int[], int);

void main()
{
	int a[max], n;
	clrscr();
	cout << "Nhap so phan tu n<" << max << ", n= ";
	cin >> n;
	nhap(a, n);
	cout << "Mang truoc khi sap xep :\n";
	xuat(a, n);
	sapxep(a, n);
	cout << "\nMang sau khi sap xep :\n";
	xuat(a, n);
}

void nhap(int a[], int n)
{
	int i;
	cout << "Nhap cac phan tu cua mang :\n";
	for (i = 0; i < n; i++)
	{
		cout << "A[" << i + 1 << "]=";
		cin >> a[i];
	}
}

void xuat(int a[], int n)
				a[i] = a[j];
				a[j] = tg;
			}
}
