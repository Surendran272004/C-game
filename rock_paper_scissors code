#include <iostream>
#include<cctype>
#include<ctime>
#include<string>
int main() {
  int choice;
  int computer;
  srand(time(NULL));
  std::cout<<"******************* ROCK PAPER SCISSORS ********************\n";
  std::cout<<"1. Rock\n";
  std::cout<<"2. PAPER\n";
  std::cout<<"3. SCISSORS\n";
  std::cout<<"Enter your choice: ";
  std::cin>>choice;
  computer=(rand() % 3)+1;
  std::cout<<"Computer choice is: "<<computer;
  std::cout<<"\n";
  if(choice==1 && computer==1){
    std::cout<<"Ha..Ha..!! Both are same choice..!! Rock..\n";
  }
  else if(choice==2 && computer==2){
    std::cout<<"Ha..Ha..!! Both are same choice..!! Paper..\n";
  }
  else if(choice==3 && computer==3){
    std::cout<<"Ha..Ha..!! Both are same choice..!! scissors..\n";
  }
  else if(choice==1 && computer==2){
    std::cout<<"You lose the game, the computer win the game!!\n";
  }
  else if(choice==2 && computer==1){
    std::cout<<"You win the game, the computer lose the game!!\n";
  }
  else if(choice==1 && computer==3){
    std::cout<<"You win the game, the computer lose the game!!\n";
  }
  else if(choice==3 && computer==1){
     std::cout<<"You lose the game, the computer win the game!!\n";
  }
  else if(choice==2 && computer==3){
    std::cout<<"You lose the game, the computer win the game!!\n";
  }
  else if(choice==3 && computer==2){
    std::cout<<"You win the game, the computer lose the game!!\n";
  }
  std::cout<<"************************************************************\n";
}
