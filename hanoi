#include <iostream>
using namespace std;

void move(char x, int n, char y)
{
	cout << x << "  --->  " << y << endl;
}
void hanoi(int n, char x, char y, char z)
{
	if (n == 1)
	{
		move(x, 1, z);
	}
	else
	{
		//将x上编号为1的n-1个圆盘移动到y上，z是辅助
		hanoi(n - 1, x, z, y);
		move(x, n, z);
		hanoi(n - 1, y, x, z);
	}

}
int main()
{
	//cout << "hello world" << endl;
	char x = 'x';
	char y = 'y';
	char z = 'z';
	hanoi(3, x, y, z);

}
