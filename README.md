# Lecture-10-Exercises
Descending stars 7 

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int i = 1; i <= 5; i++)
        {  
            for (int j = 1; j <= i; j++)
            {
                cout << "*"; 
            }
            cout << endl; 
        }


    }
Cube

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int r;
        cout << "Enter a number to find the cube" << endl;
        cin >> r;
        for (int x = 1; x <= r; x++)
        {
            cout << "\nNumber is " << x << " the cube is ";
            int y = x;
            y = y * y * y;
            cout << y;
        }

    }
9s

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int r;
        cout << "Enter a number to find the cube" << endl;
        cin >> r;
        for (int x = 1; x <= r; x++)
        {
            cout << "\nNumber is " << x << " the cube is ";
            int y = x;
            y = y * y * y;
            cout << y;
        }

    }
Rising starts 5

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        int r;
        cout << "Enter a number to find the cube" << endl;
        cin >> r;
        for (int x = 1; x <= r; x++)
        {
            cout << "\nNumber is " << x << " the cube is ";
            int y = x;
            y = y * y * y;
            cout << y;
        }

    }
Rise and Fall

    #include <iostream>
    #include <string>
    using namespace std;
    int main()
    {
        for (int i = 1; i <= 5; i++)
        { 
            for (int j = 1; j <= i; j++)
            {
                cout << "*"; 
            }
            cout << endl; 
        }

        for (int i = 1; i <= 5; i++) {
            for (int j = i; j <= 5; j++) { 
                cout << "*"; 
            }
            cout << endl;
        }


    }
