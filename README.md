#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main(){
int number, guess, guessno. = 1;
srand(time(0));
number = rand()%100 + 1;
while(guess!=number){
printf("Guess the number between 1 to 100 \n");
scanf("%d", &guess);
if(guess<number){
printf("Higher number please \n");
}
else if(guess>number){
printf("Lower number please" \n);
}
else{
printf("You have guessed the number in %d times", guessno.);
}
guessno.++;
}
return 0;
}
























}
