#include <iostream>
int main()
{
    int ile;
    
    std::cout << "Ile razy wypisac napis? ";
    std::cin >> ile;
    if( ile > 0 )
    do
    {
        std::cout << "Napis" << endl;
		std::cout << "majaksjkjaka" << endl;
        ile--;
    } while( ile > 0 );
    
    return 0;
}