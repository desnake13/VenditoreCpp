// Tonsuso Michael, 3 A inf, 10/09/2023
// Conoscendo il prezzo al kg e la quantita ci calcoliamo il prezzo finale. In base alla quantita viene applicato uno sconto.

#include <iostream>
using namespace std;

class Venditore{
    public:
        double prezzoAlKg;
        int quantita;
        
        void inserimentoValori(){
            cout << "Inserisci il prezzo al kg: ";
            cin >> prezzoAlKg;
            cout << "Inserisci la quantita di merce comprata: ";
            cin >> quantita;
        };
        
        double CalcoloPrezzoFinale(){
            double prezzoFinale = prezzoAlKg * quantita;
            return prezzoFinale;
        };
};



int main()
{
    
    Venditore obj1;
    
    obj1.inserimentoValori();
    
    
    if (obj1.quantita >= 10 && obj1.quantita < 20) {
        
        obj1.prezzoAlKg = obj1.prezzoAlKg * 0.97;
        cout << "Ecco il prezzo finale scontato del 3%: " << obj1.CalcoloPrezzoFinale() << " Euro ";
        
    } else if (obj1.quantita >= 20 && obj1.quantita < 40) {
        
        obj1.prezzoAlKg = obj1.prezzoAlKg * 0.95;
        cout << "Ecco il prezzo finale scontato del 5%: " << obj1.CalcoloPrezzoFinale() << " Euro ";
        
    } else if (obj1.quantita > 40) {
        
        obj1.prezzoAlKg = obj1.prezzoAlKg * 0.90;
        cout << "Ecco il prezzo finale scontato del 10%: " << obj1.CalcoloPrezzoFinale() << " Euro ";
        
    }

    return 0;
}
