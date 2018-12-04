Verifica 2018 4/12/2018

Effettuato un conflitto con dei commenti generati dai 2 branch principali
- master
- FIX_BUG

=== MASTER ===

#include <iostream>
using namespace std;

void main(){
	for(int i = 1; i < 11; i++){
		cout << i + "\n";
	}
	system("pause");
}

//Alexander Nettenbreijers. Verifica.
//4-12-2018
//Test
//No merge error causing comment 123

=== FIX_BUG ===

#include <iostream>
using namespace std;

void main(){
	for(int i = 1; i < 11; i++){
		cout << i + "\n";
	}
	system("pause");
}

//Alexander Nettenbreijers. Verifica.
//4-12-2018
//Test

//1
//2
//3

=== MERGED ===

#include <iostream>
using namespace std;

void main(){
	for(int i = 1; i < 11; i++){
		cout << i + "\n";
	}
	system("pause");
}

//Alexander Nettenbreijers. Verifica.
//4-12-2018
//Test
<<<<<<< HEAD
//No merge error causing comment 123
=======

//1
//2
//3
>>>>>>> FIX_BUG