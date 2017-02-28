# Snakesusing System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace snakes
{
    class Program
    {
      
        static void Main(string[] args)
        {
         
            int p1_score = 0, p2_score = 0;
            int i;
            string player1, player2;
            Console.WriteLine("enter the name of  player 1");
            Console.ReadLine();
            Console.WriteLine("enter the name of the player 2");
            Console.ReadLine();
            Console.WriteLine("the position of player1 and player2 is 0 initially");

            while (p1_score < 100 && p2_score < 100)
            {

                Console.WriteLine(" player1 ", " It is your turn press any key to play ");
                Console.Read();
                Console.WriteLine("your score is  p1_score");
                Console.WriteLine ("player2 ","it is your turn press any key to play");
                Console.Read();
                Console.WriteLine("your score is  p2_score");

            }
            if (p1_score > p2_score)
            {
                Console.WriteLine(" player1 is the winner");
            }
            if (p2_score > p1_score)
            {
                Console.WriteLine("player2 is the winner");
            }
            if (p1_score == p2_score)
            {
                Console.WriteLine("match is draw");
            }

        }
        
          static int randomfunc(int score)

        {  
            int random;
            random = static int rand()% MAX_NUM;
            Console.WriteLine("your number is random");
            score = random + score;
            switch (score)
            {
            
                case 98:
                    score = 28;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 95:
                    score = 24;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 92:
                    score = 51;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 83:
                    score = 19;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 73:
                    score = 1;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 69:
                    score = 33;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 64:
                    score = 36;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 59:
                    score = 17;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 55:
                    score = 7;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 52:
                    score = 11;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 48:
                    score = 9;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 46:
                    score = 5;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 44:
                    score = 22;
                    Console.WriteLine("you ran into a snake!");

                    break;
                case 8:
                    score = 26;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 21:
                    score = 82;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 43:
                    score = 77;
                    Console.WriteLine("luckyyy boy u got ladder");
                    break;
                case 50:
                    score = 91;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 54:
                    score = 93;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 62:
                    score = 96;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 66:
                    score = 87;
                    Console.WriteLine("luckyyy boy u got ladder");

                    break;
                case 80:
                    score = 100;
                    Console.WriteLine("luckyyy boy u got ladder");
                    break;

            }
            Console.ReadLine();
        }

    }
}

