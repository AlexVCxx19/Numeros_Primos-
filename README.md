#include <iostream>

using namespace std;

int main()
{
    float calificaciones,calificaciones2,calificaciones3,resultado,promedio;
    cout<<"Matematicas :"<<endl;
    cin>>calificaciones;
    cout<<"El alumno saco en matematicas"<<endl<<calificaciones<<endl;
    cout<<"Ingles :"<<endl;
    cin>>calificaciones2;
    cout<<"El alumno saco en ingles"<<endl<<calificaciones2<<endl;
    cout<<"Historia :"<<endl;
    cin>>calificaciones3;
    cout<<"El alumno saco en historia"<<endl<<calificaciones3<<endl;

//Empesamos con if para saber el minimo numero que el alumno tiene que tener para aprobar
    if(calificaciones>=65)
    {
        cout<<"El alumno aprobo matematicas"<<endl;
    }
    else
    {
        if(calificaciones<65)
        {
            cout<<"El alumno reprobo matematicas"<<endl;
        }
    }
//Se abre otro if
    if(calificaciones2>=65)
    {
        cout<<"El alumno apruebo ingles"<<endl;
    }
    else
    {
        if(calificaciones2<65)
        {
            cout<<"El alumno reprobo ingles"<<endl;

        }
    }
//Otro if
    if(calificaciones3>=65)
    {
        cout<<"El alumno apruebo historia"<<endl;
    }
    else
    {
        if(calificaciones3<65)
        {
            cout<<"El alumno reprobo historia"<<endl;

        }
    }
//Sacar el prometdio
    cout<<"El promedio es"<<endl<<(calificaciones+calificaciones2+calificaciones3)/3<<endl;





    return 0;
}
