using System;
    namespace operatorler
{
    class Program   
    {
        static void Main(string[] args)
        {
           Console.WriteLine("atama ve işleme atama***");
            //atama ve işlemli atama
            int x = 3;
            int y = 3;
            y = y+3;

            Console.WriteLine(y);
            y +=2;
            Console.WriteLine(y);
            y /=1;
            Console.WriteLine(y);
            x *=2;
            Console.WriteLine(x);


        Console.WriteLine("mantıksal operatorler****");
        //mantıksal operatorler
        // ||,&&, !
        bool isSuccess = true;
        bool isCompleted = false;

        if(isSuccess && isCompleted)
            Console.WriteLine("perfect");

        if(isSuccess || isCompleted)
            Console.WriteLine("great");    
        if(isSuccess && !isCompleted)
            Console.WriteLine("fine");
        
        Console.WriteLine("ilişkiseel operatorler****");
        //ilişkisel operatorler
        // <,>,<=,>=,==,!=
        int a =3;
        int b =4;
        bool sonuc = a<b;
        Console.WriteLine(sonuc);
        sonuc = a>b;
        Console.WriteLine(sonuc);
        sonuc = a>=b;
        Console.WriteLine(sonuc);
        sonuc = a<=b;
        Console.WriteLine(sonuc);
        sonuc= a==b;
        Console.WriteLine(sonuc);
        sonuc= a!=b;
        Console.WriteLine(sonuc);

    //aritmetik operatorler (+, -, *, /, %, ++, --) matematik işlemleri kolay
    

        }
    }  
}
