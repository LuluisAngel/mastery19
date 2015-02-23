# mastery19
Here's the code
      
      // Luis Angel Aguilar Carrillo A01225421
      #include <iostream>
      
      using namespace std;
      
      int main (){
      
      	int x, y, z, result=0, i=0;
      
      	cout << "Introduce un numero" << endl;
      	cin >> x;
      
      	cout << "Introduce otro numero" << endl;
      	cin >> y;
      
      	z = (y-x)+1;
      
      
      	while (i<z){				// Esa es la condición del while, y va a seguir haciendo
      		
      		result = result + x;    // esta suma hasta que la condición sea cumplida.
      		x = x+1;
      		i= i+1;					// Este es el contador
      
      	}
      		
      		cout << "La suma de " << x << " a " << y <<" = " << result << endl;
      	
      	return 0;
      }
