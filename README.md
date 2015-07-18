# entrega-1
Primera entrega programación orientada a objetos, programa que dice el tamaño y rango de distintos tipos de datos.







using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using System.Threading.Tasks;


namespace Entrega1

{

    class Program

    {

        static void Main(string[] args)

        {

            Console.WriteLine("Porfavor introduzca el tipo de dato del que quiera informacion");

            Console.WriteLine("");

            Console.WriteLine("utilice letras minusculas unicamente");

            string dato = Console.ReadLine();


            switch (dato)
            {
                    case "byte":
                    Console.WriteLine("Tamaño: 8");
                    Console.WriteLine("Rango: 0 a 255");
                    break;

                    case "sbyte":
                    Console.WriteLine("Tamaño: 8");
                    Console.WriteLine("Rango: -128 a 127");
                    break;

                    case "int":
                    Console.WriteLine("Tamaño: 32");
                    Console.WriteLine("Rango: -2,147,483,648 a 2,147,483,647");
                    break;

                    case "uint":
                    Console.WriteLine("Tamaño: 32");
                    Console.WriteLine("Rango: 0 a 4294967295");
                    break;

                    case "short":
                    Console.WriteLine("Tamaño: 16");
                    Console.WriteLine("Rango: -32,768 a 32,767");
                    break;

                    case "ushort":
                    Console.WriteLine("Tamaño: 16");
                    Console.WriteLine("Rango: 0 a 65535");
                    break;

                    case "long":
                    Console.WriteLine("Tamaño: 64");
                    Console.WriteLine("Rango: -9223372036854775808 a 9223372036854775807");
                    break;

                    case "ulong":
                    Console.WriteLine("Tamaño: 64");
                    Console.WriteLine("Rango: 0 a 18446744073709551615");
                    break;

                    case "float":
                    Console.WriteLine("Tamaño: 32");
                    Console.WriteLine("Rango: -3.402823e38 a 3.402823e38");
                    break;

                    case "double":
                    Console.WriteLine("Tamaño: 64");
                    Console.WriteLine("Rango: -1.79769313486232e308 a 1.79769313486232e308");
                    break;

                    case "char":
                    Console.WriteLine("Tamaño: 16");
                    Console.WriteLine("Rango:Unicode symbols used in text");
                    break;

                    case "bool":
                    Console.WriteLine("Tamaño: 8");
                    Console.WriteLine("Rango:Verdadero o falso");
                    break;

                    case "decimal":
                    Console.WriteLine("Tamaño: 128");
                    Console.WriteLine("Rango:±1.0 × 10e−28 to ±7.9 × 10e28");
                    break;

                    default:
                    Console.WriteLine("El dato no ha sido reconocido, por favor reviselo");
                    break;
            }
            Console.WriteLine("");
            Console.WriteLine("presione enter para salir");
            Console.ReadLine();
        }
    }
}
