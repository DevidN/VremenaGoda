# VremenaGoda
Создать программу с пользовательским меню для выбора времен года
#include <iostream>
using namespace std;

int main()
{
	setlocale(0, "");
	cout << "[-]Выберите время года:\n\n ";
	cout << "[1] Лето \n";
	cout << "[2] Осень \n";
	cout << "[3] Зима \n";
	cout << "[4] Весна \n";
	int a;
	cin >> a;
	if (a == 1)
	{
		system("cls");
		cout << "Играй в доту";
	}
	else if (a == 2)
	{
		system("cls");
		cout << "Пора учиться :((";
	}
	else if (a == 3)
	{
		system("cls");
		cout << "Опять новый год 1 празднуешь?";
	}
	else if (a == 4)
	{
		system("cls");
		cout << "Скоро лето";
	}
	 
	
	int _; cin >> _;
	return main ();
		
}
