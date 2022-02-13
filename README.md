# Calculator
Calculator in C++
Code explanation:
"#include "Calculator.h" is to include Another file in project. If i didn't include Calculator file, I wouldn/t be able to write this:
Calculator c;
    while (true)
    {
        cin >> x >> oper >> y;
        if (oper == '/' && y == 0)
        {
            cout << "You can't divide by 0" << endl;
            continue;
        }
        else
        {
            result = c.Calculate(x, oper, y);
        }
        cout << "Result is: " << result << endl;
         }

    return 0;
    
    "std::cout" is to show text in console. This is like Console.WriteLine in C#.
   "endl" is something like you press enter key.
    I hope you understand
    
    
    
