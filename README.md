#include "iostream"
using namespace std;
 
int main()
{
setlocale(LC_ALL, "rus");
 
int enterNumber = 0;
 
cout << "Enter number (from 1 to 9999): ";
cin >> enterNumber;
 
if (enterNumber <= 0 ||enterNumber > 9999) 
 cout << "The number is not in the range from 1 to 9999!\n";
else 
{
 cout << "\nYou entered: ";

 if ((enterNumber / 1000)% 10 == 1) cout << "One thousand";
 else if ((enterNumber / 1000)% 10 == 2) cout << "Two thousand";
 else if ((enterNumber / 1000)% 10 == 3) cout << "Three thousand";
 else if ((enterNumber / 1000)% 10 == 4) cout << "Four thousand";
 else if ((enterNumber / 1000)% 10 == 5) cout << "Five thousand";
 else if ((enterNumber / 1000)% 10 == 6) cout << "Six thousand";
 else if ((enterNumber / 1000)% 10 == 7) cout << "Seven thousand";
 else if ((enterNumber / 1000)% 10 == 8) cout << "Eight thousand";
 else if ((enterNumber / 1000)% 10 == 9) cout << "Nine thousand";
 
 
 if ((enterNumber / 100)% 10 == 1) cout << "one hundred";
 else if ((enterNumber / 100)% 10 == 2) cout << " two hundred";
 else if ((enterNumber / 100)% 10 == 3) cout << " three hundred";
 else if ((enterNumber / 100)% 10 == 4) cout << " four hundred";
 else if ((enterNumber / 100)% 10 == 5) cout << " five hundred";
 else if ((enterNumber / 100)% 10 == 6) cout << " six hundred";
 else if ((enterNumber / 100)% 10 == 7) cout << " seven hundred";
 else if ((enterNumber / 100)% 10 == 8) cout << " eight hundred";
 else if ((enterNumber / 100)% 10 == 9) cout << " nine hundred";
 
 if ((enterNumber / 10)% 10 == 1)
 {
 if (enterNumber% 10 == 0) cout << "ten rublei";
 else if (enterNumber% 10 == 1) cout << " eleven rublei";
 else if (enterNumber% 10 == 2) cout << " twelve rublei";
 else if (enterNumber% 10 == 3) cout << " thirteen rublei";
 else if (enterNumber% 10 == 4) cout << " fourteen rublei";
 else if (enterNumber% 10 == 5) cout << " fifteen rublei";
 else if (enterNumber% 10 == 6) cout << " sixteen rublei";
 else if (enterNumber% 10 == 7) cout << " seventeen rublei";
 else if (enterNumber% 10 == 8) cout << " eighteen rublei";
 else if (enterNumber% 10 == 9) cout << " nineteen rublei";
 }
 
 if ((enterNumber / 10)% 10 == 2) cout << "twenty";
 else if ((enterNumber / 10)% 10 == 3) cout << " thirty";
 else if ((enterNumber / 10)% 10 == 4) cout << " forty";
 else if ((enterNumber / 10)% 10 == 5) cout << " fifty";
 else if ((enterNumber / 10)% 10 == 6) cout << " sixty";
 else if ((enterNumber / 10)% 10 == 7) cout << " seventy";
 else if ((enterNumber / 10)% 10 == 8) cout << " eighty";
 else if ((enterNumber / 10)% 10 == 9) cout << " ninety";
 
 if ((enterNumber / 10) % 10 != 1)
 {
 if (enterNumber% 10 == 0) cout << "rublei";
 else if (enterNumber% 10 == 1) cout << " one rub";
 else if (enterNumber% 10 == 2) cout << " two rublia";
 else if (enterNumber% 10 == 3) cout << " three rublia";
 else if (enterNumber% 10 == 4) cout << " four rublia";
 else if (enterNumber% 10 == 5) cout << " five rublei";
 else if (enterNumber% 10 == 6) cout << " six rublei";
 else if (enterNumber% 10 == 7) cout << " seven rublei";
 else if (enterNumber% 10 == 8) cout << " eight rublei";
 else cout << " nine rublei";
 }
}
 
cout << endl << endl;
return 0;
}
 
![Screenshot (130)](https://user-images.githubusercontent.com/90500831/136836443-64f4c78b-d327-4645-8c34-8ef90774e9df.png)

