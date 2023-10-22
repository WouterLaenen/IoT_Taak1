#include <iostream>
#include <cstdlib>
#include <ctime>

int main() {
    // Initialiseer de random number generator met de huidige tijd als seed
    std::srand(static_cast<unsigned>(std::time(nullptr)));

    // Genereer een willekeurig getal tussen 1 en 5
    int random_number = std::rand() % 5 + 1;

    // Druk het willekeurige getal af
    std::cout << "Het willekeurige getal is: " << random_number << std::endl;

    return 0;
}
