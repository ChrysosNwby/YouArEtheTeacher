YouArEtheTeacher
================

I'm a niewbie but, find a method to myself to teach myself to code! :) enjoyyy (I'm From belgium)

#include <iostream>

using namespace std;

void StateOfMind ();
void HoeveelJaar (int a)
{
    cout << "Hoeveel jaar ben je?:" << a;

}
void GebuistOfGeslaagd (int b)
{
    cout << "Als je op Mechanica onder de 50 hebt\n" << "ben je gebuist...\n";
    cout << "\nJij hebt op Mechanica" << b;
}




int main ()
{
    cout << "Hallo Doga Cakir\n";
    cout << "Je bent geslaagd op je eerste test!\n\n";
    cout << "Bravo!!!!!" << endl;

    int minimumScore;
    minimumScore = 50;

    cout << "Je hebt een minimum score van\n";
    cout << minimumScore;

    minimumScore = 50 + 50;

    cout << "\nMinimum score is gestogen met 50 punten\n";
    cout << "Je behaalde score is...\n\n";
    cout << minimumScore << endl;

    minimumScore = 100 - 20;

    cout << "\nOmdat je paar fouten hebt gemaakt is je minimum score 20 punten gedaald...\n";
    cout << "Je minimum score is nu...\n\n";
    cout << minimumScore << endl;

    cout << "\nGoed gedaan volg nu je volgende les en kom weer terug!!!\n";
    cout << "Maak nu een simpele rekenmachine voor 10 punten" << endl;

    int a;
    int b;
    int som;

    cout << "Toets een getal in:";
    cin >> a;
    cout << "Toets nog een getal in:";
    cin >> b;
    cout << "De som van deze getallen is:";
    som=a+b;
    cout << som << endl;
    cout << "\n\n";

    minimumScore = minimumScore - 10;
    cout << "Door het fout maken van deze rekenmachiene\n";
    cout << "heb je 10 punten verloren!!!";
    cout << "Je hebt nu de een minimumscore van";
    cout << minimumScore << endl;

    cout << "\n\n";
    cout << "Maak nu een functie van een void\n\n";

    cout << "Ik voel me vandaag\n";
    StateOfMind ();

    cout << "Opdracht van functie Void goed gedaan!\n";
    cout << "Je minimum score word met 5 punten erbij geteld";
    cout << "Je hebt nu\n";
    minimumScore = minimumScore + 5;
    cout << minimumScore << endl;

    cout << "\nMaak nu een functie weer met void alleen met een parameter erbij\n";
    HoeveelJaar (16);
    cout << "\n\nDoor het klein aantal fouten krijg je geen punten!\n" << "Herhaal de deel parameters!" << endl;
    GebuistOfGeslaagd (35);
    cout << "\n\nHerhaal nog maar een paar keer dan heb" << "Je het wel onder de knie" << "\nDus jij ben gebuist op mechanica";
    cout << "\nHAHAHAHAHAHHAHA" << "\nLol Joke" << endl;


    return 0;
}
    void StateOfMind ()
    {
        cout << "Goed";
    }







