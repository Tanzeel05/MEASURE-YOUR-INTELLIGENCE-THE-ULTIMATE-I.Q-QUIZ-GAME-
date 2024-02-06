# Quiz-Game
Welcome to the C Quiz Game Repo! Dive into animated, challenging gameplay with customizable difficulty levels and high score tracking. Join our community, contribute, and download now for endless fun!
#include <stdio.h>
#include <stdlib.h>
#include <ctype.h>
#include <time.h>
#include <windows.h>
#include <conio.h>



#define MAX_QUESTIONS 10
#define MAX_NAME_LENGTH 20

void showAd() {
    int adNumber =  rand() % 5; // Randomly select an ad
    switch (adNumber) {
        case 0:
        	system("cls");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       BUY COLA FAST TODAY AND EXPERIENCE THE UNMATCHED REFRESHMENT OF THE FINEST COLA      \n");
    printf("\t\t\t\t\t\t       IN FAST NUCES! ENDORSED BY THE ONE AND ONLY: ATIYA JOKHIO. NOW FEATURING NEW         \n");
    printf("\t\t\t\t\t\t       FLAVORS:                                                                             \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - Sparkling Citrus Burst                                                             \n");
    printf("\t\t\t\t\t\t       - Vanilla Dream Delight                                                              \n");
    printf("\t\t\t\t\t\t       - Cherry Bliss Explosion                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! LIMITED STOCK AVAILABLE!                                                   \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.buycolafast.com for exclusive offers and promotions!        \n");
    printf("\t\t\t\t\t\t       Follow us on social media: @BuyColaFast                                              \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
	            break;
        case 1:
        	system("cls");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       ENROLL YOURSELF IN FAST NATIONAL UNIVERSITY NOW. THE BEST CS AND IT UNIVERISTY.      \n");
    printf("\t\t\t\t\t\t       PRESENT IN KARACHI, ISLAMABAD, LAHORE, FAISALABAD, PESHAWAR. GUARANTEES THE          \n");
    printf("\t\t\t\t\t\t       FOLLOWING:                                                                             \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - FUTURE SAFETY                                                             \n");
    printf("\t\t\t\t\t\t       - JOB OPPORTUNITES                                                              \n");
    printf("\t\t\t\t\t\t       - SKILLS                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! LIMITED SEATS AVAILABLE!                                                   \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.fastnu.edu.pk for further information!        \n");
    printf("\t\t\t\t\t\t       Follow us on social media: @FastNationalUniversity                                              \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");


	     break;
        case 2:
        	system("cls");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       SUPPORT PALESTINE, SUPPORT HUMANITY      \n");
    printf("\t\t\t\t\t\t       CONTRIBUTE TO STOP THE GENOCIDE!!!         \n");
    printf("\t\t\t\t\t\t       DONATE VIA:                                                                             \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - IMAM-PAY                                                             \n");
    printf("\t\t\t\t\t\t       - AL-TANZEEL BANK                                                              \n");
    printf("\t\t\t\t\t\t       - ABDULLAH GROUP OF COMPANIES                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! ! !                                                  \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.savepalestine.com for further information!        \n");
    printf("\t\t\t\t\t\t       Support this cause in social media too, make a change.                                             \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");

            break;
        case 3:
        	system("cls");
            
   
     printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       VISIT PAKISTAN, THE LAND OF HOSPITALITY, BEAUTY AND PEACE.      \n");
    printf("\t\t\t\t\t\t       PROS: CHEAP, EASY ACCESS TO HOTELS/MOTELS, DELICIOUS FOOD, GREAT CULTURE         \n");
    printf("\t\t\t\t\t\t       FRIENDLY ENVIRONMENT, PLEASANT WEATHER.                                                                            \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - VALLEYS                                                             \n");
    printf("\t\t\t\t\t\t       - LAKES                                                              \n");
    printf("\t\t\t\t\t\t       - SEA                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! PLAN YOUR VACATIONS NOW!                                                   \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.visitpakistan.com for exclusive offers and promotions!        \n");
    printf("\t\t\t\t\t\t       Follow us on social media: @PakistanZindabad                                              \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");


            break;
        case 4:
        	system("cls");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       VISIT OUR AL-JOKHIO MOTORS TODAY TO GET EXCLUSIVE DISCOUNTED DEALS      \n");
    printf("\t\t\t\t\t\t       ALL OVER IN PAKISTAN! ALL CATEGORIES AVAILABLE WITH INSURANCE.           \n");
    printf("\t\t\t\t\t\t       CATGEORIES:                                                                             \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - SUVs                                                             \n");
    printf("\t\t\t\t\t\t       - Trucks                                                              \n");
    printf("\t\t\t\t\t\t       - Sedans                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! MAKE A DEAL NOW!                                                   \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.cars.pk for exclusive offers and promotions!        \n");
    printf("\t\t\t\t\t\t       Follow us on social media: @CarsPK                                              \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");


             break;
        default:
        	system("cls");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       VISIT OUR SHOP AT SHAH LATIF TOWN TO GET THE BEST DEAL FOR LAPTOPS!      \n");
    printf("\t\t\t\t\t\t       VARIETY OF PRICE RANGE AVIALABLE AND ALL SPECIFICATIONS AVAILABLE.        \n");
    printf("\t\t\t\t\t\t       BRANDS:                                                                             \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       - DELL                                                             \n");
    printf("\t\t\t\t\t\t       - HP                                                              \n");
    printf("\t\t\t\t\t\t       - LENOVO                                                             \n");
    printf("\n\n\n"); 
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       HURRY UP! LIMITED STOCK AVAILABLE!                                                   \n");
    printf("\n\n\n");
	printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\t\t\t\t\t\t       Visit our website at www.laptops.com for exclusive offers and promotions!        \n");
    printf("\t\t\t\t\t\t       Follow us on social media: @BuyLaptops                                              \n");
    printf("\t\t\t\t\t\t                                                                                           \n");
    printf("\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t\t                                A D V E R T I S E M E N T                                  \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");

     }
    Sleep(10000); // Wait for 10 seconds to display the ad
}

struct Question {
    char questionText[200];
    char options[4][50];
    char correctOption;
};


struct Question easyQuestions[MAX_QUESTIONS] = {
    {"What is the capital of France?", {"A. London", "B. Paris", "C. Berlin", "D. Rome"}, 'B'},
    {"Which planet is known as the Red Planet?", {"A. Venus", "B. Jupiter", "C. Mars", "D. Saturn"}, 'C'},
    {"What is the largest mammal on Earth?", {"A. Elephant", "B. Giraffe", "C. Blue Whale", "D. Dolphin"}, 'C'},
    {"Which one is Miss Atiya's favorite batch?'", {"A. 20K", "B. 23K", "C. 19K", "D. None"}, 'C'},
    {"What is the the capital of Pakistan?", {"A. Karachi", "B. Islamabad", "C. Jamshoro", "D. Lahore"}, 'B'},
    {"Miss Atiya has a Master's degree of?'", {"A. MS(CSE))", "B. MS(IT)", "C. MS(NA)", "D. MS(CC)"}, 'A'},
    {"When was C Language developed?", {"A. 1972", "B. 1989", "C. 1968", "D. 1962"}, 'A'},
    {"This IQ Quiz Game is created by members of?", {"A. Front Benchers", "B. Shararti Bachay", "C. Girls", "D. None"}, 'B'},
    {"Sun is a?", {"A. Plantet", "B. Orbit", "C. Galaxy", "D. Star"}, 'D'},
    {"Total number of PF Labs in FAST NU?", {"A. 10", "B. 13", "C. 15", "D. 12"}, 'D'},
	
    // Add more easy questions here
};

struct Question mediumQuestions[MAX_QUESTIONS] = {
    {"Who wrote the play 'Romeo and Juliet'?", {"A. William Shakespeare", "B. Charles Dickens", "C. Jane Austen", "D. Mark Twain"}, 'A'},
    {"What is the chemical symbol for gold?", {"A. Au", "B. Ag", "C. Fe", "D. Hg"}, 'A'},
    {"Which gas do plants absorb from the atmosphere during photosynthesis?", {"A. Carbon dioxide (CO2)", "B. Oxygen (O2)", "C. Nitrogen (N2)", "D. Hydrogen (H2)"}, 'A'},
    {"Which one of the four is least like the other four?(snake, cow, tiger,  bear)", {"A. snake", "B. cow", "C. tiger", "D. bear "}, 'A'},
    {"If we re-arrange the letters BARBIT, you would have a name of a? ", {"A. Country", "B. City", "C. Animal", "D. River"}, 'C'},
    {"Which one of the four letters is least like the other three(F,C,D,E) ? ", {"A. F", "B. C", "C. D", "D. E"}, 'D'},
    {"Which one of the four makes the best comparison? Milk is to glass as letter is to? ", {"A. Stamp", "B. Pen", "C. Envelope", "D. Book"}, 'C'},
    {"Which one of the four makes the best comparison? CAACCAC is to 3113313 then CACAACAC is ?", {"A. 31313113", "B. 31311313", "C. 33133131", "D. 13133311"}, 'B'},
    {"Some months have 31 days; how many have 28? ", {"A. 1", "B. 6", "C. 7", "D. 12"}, 'D'},
    {"How many birthdays does a average man have? ", {"A. one", "B. every year", "C. twice a year", "D. infinite"}, 'A'},
    // Add more medium questions here
};

struct Question hardQuestions[MAX_QUESTIONS] = {
    {"In which year did Christopher Columbus first arrive in the Americas?", {"A. 1492", "B. 1620", "C. 1776", "D. 1812"}, 'A'},
    {"What is the capital of Australia?", {"A. Sydney", "B. Melbourne", "C. Canberra", "D. Brisbane"}, 'C'},
    {"Who was the first woman to fly solo across the Atlantic Ocean?", {"A. Amelia Earhart", "B. Bessie Coleman", "C. Harriet Quimby", "D. Jacqueline Cochran"}, 'A'},
    {"What is the currency of Malaysia?", {"A. Rupees", "B. Ringgit", "C. Dollars", "D. Lira"}, 'B'},
    {"A car travels at a speed of 70 MPH for 3 hours. How far will the car travel in 4 hours?", {"A. 210 miles", "B. 70 miles", "C. 280 miles", "D. 300 miles"}, 'C'},
    {"C language was a better version of which language?", {"A. A Language", "B. B Language", "C. Assembly Language", "D. Machine Language"}, 'B'},
    {"Which country had a wall in between the center of their city?", {"A. China", "B. Germany", "C. Russia", "D. Australia"}, 'B'},
    {"How many Constitutions of Pakistan are there?", {"A. 1", "B. 3 ", "C. 2", "D. 4"}, 'B'},
    {"What is the meaning of the idiom to kick the bucket?", {"A. To die", "B. To start a new project", "C. To get angry", "D. To make a mistake"}, 'D'},
    {"Which city is known as the Big Apple?", {"A. Toronto", "B. Los Angeles", "C. New York", "D. London"}, 'C'}
    // Add more hard questions here
};

// Function to display the score with a beep and update high score
void displayScore(float score, char playerName[MAX_NAME_LENGTH]);

// Function to display the help message with a beep
void help();

// Function to write the score to a file and update high score
void writeScore(float score, char playerName[MAX_NAME_LENGTH]);

// Function to retrieve the high score from a file
void retrieveHighScore(float *highScore, char highScoreName[MAX_NAME_LENGTH]);

// Function to save the high score to a file
void saveHighScore(float highScore, char highScoreName[MAX_NAME_LENGTH]);

// Function to play a beep sound with Windows API
void customBeep(int frequency, int duration);

// Function to print the header of the interface
void printHeader();

// Function to display a loading animation
void loadingAnimation();

int main() {
    char choice;
    char choice2 = 'Y'; // Declare choice2 here

    int countQ, countR;
    float score;
    char playerName[MAX_NAME_LENGTH];
    char difficulty;

    struct Question *questions; // Pointer to the selected set of questions

    struct Question *easySet = easyQuestions;
    struct Question *mediumSet = mediumQuestions;
    struct Question *hardSet = hardQuestions;

    do {
        system("cls");
        welcomeAnimation(); // Add a function for welcome animation

       // printHeader();
        printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n");
    printf("\n");
    printf("\t\t\t\t\t                         C H O O S E   A N   O P T I O N !!!                               \n");
    printf("\n");
    printf("\n");
    printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    printf("\n\n\n\n");
    printf("\t\t\t\t\t\t\t         S   -   S T A R T   G A M E       ");
    printf("\n\n\n\n");
    printf("\t\t\t\t\t\t\t         V   -   V I E W  S C O R E        ");
    printf("\n\n\n\n");
	printf("\t\t\t\t\t\t\t         H   -   H E L P                   ");
	printf("\n\n\n\n");
    printf("\t\t\t\t\t\t\t         Q   -   Q U I T                   ");
    printf("\n\n\n\n");
	printf("+----------------------------------------------------------------------------------------------------------------------------------------------------------------------+\n");
    


        while ((choice = toupper(getchar())) == '\n'); // Clear input buffer

        if (choice == 'V') {
            displayScore(score, playerName);
        } else if (choice == 'Q') {
            return 0;
        } else if (choice == 'H') {
            help();
        } else if (choice == 'S') {
            loadingAnimation();
            system("cls");
            printf("\n\t\t\t\t\t\t\t\t  Enter your Name: ");
            customBeep(500, 300); // Beep before prompting for the name
            scanf("%s", playerName);

            printf("\n\t\t\t\t\t\t\t\t  Select difficulty level:\n");
            printf("\t\t\t\t\t\t\t\t  E - Easy\n");
            printf("\t\t\t\t\t\t\t\t  M - Medium\n");
            printf("\t\t\t\t\t\t\t\t  H - Hard\n");
            printf("\n\t\t\t\t\t\t\t\t  Enter your choice: ");
            scanf(" %c", &difficulty);
            
            while (getchar() != '\n'); // Clear input buffer

            switch (toupper(difficulty)) {
            case 'E':
                questions = easySet;
                break;
            case 'M':
                questions = mediumSet;
                break;
            case 'H':
                questions = hardSet;
                break;
            default:
                printf("\n\t\t\t\t  Invalid difficulty level.\n");
                
                customBeep(500, 300); // Beep after displaying error message
                customBeep(500, 300);
                customBeep(500, 300);
                customBeep(500, 300);
                customBeep(500, 300);
                
                  printf("\n\t\t\t\t  Using easy as default :) \n");
                questions = easySet;
                        Sleep(100); // Adjust the sleep duration for the desired speed
        Sleep(100); // Adjust the sleep duration for the desired speed
        Sleep(100); // Adjust the sleep duration for the desired speed

            }
showAd();
            countQ = countR = 0;
            score = 0.0;

            int i;
            for (i = 0; i < MAX_QUESTIONS; i++) {
            	            questionTransitionAnimation();  // Add the transition animation here

                system("cls");
                printf("\n\t\t\t\t\t\t\t\t  Question %d: %s\n\n", i + 1, questions[i].questionText);
                int j;
                for (j = 0; j < 4; j++) {
                    printf("\t\t\t\t\t\t\t\t  %s\n", questions[i].options[j]);
                }

                printf("\n\t\t\t\t\t\t\t\t  Enter your answer: ");
                customBeep(500, 300); // Beep before waiting for user input
                char answer = toupper(getchar());
                while (getchar() != '\n'); // Clear input buffer

                // Check if the user answered correctly
                if (answer == questions[i].correctOption) {
                    printf("\n\t\t\t\t\t\t\t\t  Correct!");
                    customBeep(1000, 500); // Nice sound for correct answer
                    countR++;
                } else {
                    printf("\n\t\t\t\t\t\t\t\t  Wrong! The correct answer is %c.", questions[i].correctOption);
                    customBeep(200, 1000); // Losing sound for the wrong answer
                }

                countQ++;
                customBeep(500, 300); // Beep before waiting for user input
            }

            score = ((float)countR / countQ) * 100;

            if (score < 0) {
                score = 0;
            }

            displayScore(score, playerName);

            printf("\n\t\t\t\t  NEXT PLAY? (Y/N): ");
            customBeep(500, 300); // Beep after prompting for next play
            choice2 = toupper(getchar());

            if (choice2 != 'Y') {
                writeScore(score, playerName);
            }
        } else {
            printf("\n\t\t\t\t  Enter the right key");
            customBeep(500, 300); // Beep after displaying an error message
            while (getchar() != '\n'); // Clear input buffer
        }
    } while (choice2 != 'N');

    return 0;
}

// Function to display the score with a beep and update the high score
void displayScore(float score, char playerName[MAX_NAME_LENGTH]) {
    system("cls");
    printf("\n\t\t ");
    customBeep(500, 300); // Beep before displaying the score
    printf("\n\t\t %s has secured a score of %.2f", playerName, score);
    customBeep(500, 300); // Beep after displaying the score

    // Check and update the high score
    writeScore(score, playerName);

    // Display the high score from "highscore.txt" file
    float highScore;
    char highScoreName[MAX_NAME_LENGTH];
    retrieveHighScore(&highScore, highScoreName);

    printf("\n\t\t High Score: %.2f by %s\n", highScore, highScoreName);

    printf("\n\t\t ");
    printf("\n\t\t Press Enter to continue...");

    // Clear the input buffer
    while (getchar() != '\n');
    getchar(); // Read and ignore the Enter key
}

// Function to display the help message with a beep
void help() {
    system("cls");
    printf("\n\n\n\n\n\n\n\n\n\n\n");
    printf("\n\t\t\t\t\t\t\t   This game is very easy to play. You'll be asked some general");
    printf("\n\n\t\t\t\t\t\t\t   knowledge questions, and you have to choose the correct option.");
    printf("\n\n\t\t\t\t\t\t\t   Your score will be calculated at the end based on your answers.");
    printf("\n\n\t\t\t\t\t\t\t   If you achieve the highest score, your score will be recorded.");
    customBeep(500, 300); // Beep after displaying the help message
    printf("\n\n\n\n\t\t\t\t\t\t\t\t\t\t   BEST OF LUCK!");

    printf("\n\n\n\n\t\t\t\t\t\t\t   Press Enter to continue...");

    while (getchar() != '\n');
    getchar(); // Read and ignore the Enter key
}

// Function to write the score to a file and update the high score
void writeScore(float score, char playerName[MAX_NAME_LENGTH]) {
    float currentScore;
    char currentName[MAX_NAME_LENGTH];

    FILE *scoreFile = fopen("allscores.txt", "a+"); // Corrected the filename
    if (scoreFile != NULL) {
        fprintf(scoreFile, "%s %.2f\n", playerName, score);
        fclose(scoreFile);

        // Check if the current score is higher than the existing high score
        float highScore;
        char highScoreName[MAX_NAME_LENGTH];
        retrieveHighScore(&highScore, highScoreName);

        if (score > highScore) {
            saveHighScore(score, playerName);
        }
    }
}


// Function to retrieve the high score from a file
void retrieveHighScore(float *highScore, char highScoreName[MAX_NAME_LENGTH]) {
    FILE *highScoreFile = fopen("highscore.txt", "r");
    if (highScoreFile != NULL) {
        fscanf(highScoreFile, "%s %f", highScoreName, highScore);
        fclose(highScoreFile);
    } else {
        // If the file doesn't exist, set default values
        *highScore = 0.0;
        strcpy(highScoreName, "No one");
    }
}


// Function to save the high score to a file
void saveHighScore(float highScore, char highScoreName[MAX_NAME_LENGTH]) {
    FILE *highScoreFile = fopen("highscore.txt", "w");
    if (highScoreFile != NULL) {
        fprintf(highScoreFile, "%s %.2f\n", highScoreName, highScore);
        fclose(highScoreFile);
    }
}


// Function to play a beep sound with Windows API
void customBeep(int frequency, int duration) {
    Beep(frequency, duration);
}






void loadingAnimation() {
    printf("\n\t\t\t\t\t\t\t\t  LOADING YOUR GAME");

    int numDots = 7; // Number of dots in the animation
    int bounceDistance = 7; // Number of spaces to bounce the dots
int i;
    for ( i = 0; i < 2; i++) {
    	int j;
        for ( j = 0; j < numDots; j++) {
            printf("\033[1;32m."); // Set color to bright green (modify based on your console)
            fflush(stdout);
            usleep(150000); // Adjusted sleep duration for a slightly faster animation
        }

        for ( j = 0; j < bounceDistance; j++) {
            printf("\b \b"); // Move back to erase the dots
            fflush(stdout);
            usleep(100000); // Short pause between bounces
        }

        for ( j = 0; j < bounceDistance; j++) {
            printf("\b\b."); // Move forward to redraw the dots
            fflush(stdout);
            usleep(100000); // Short pause between bounces
        }
    }

    printf("\033[0m\n"); // Reset color (optional, based on your console)
    
}

void welcomeAnimation() {
	printf("\n\n\t\t\t\t\t\t\t  ------------------------------------------------------");
    printf("\n\n\t\t\t\t\t\t\t  Welcome to the I.Q ( Intelligent Quotient ) Quiz Game!");
    printf("\n\n\t\t\t\t\t\t\t  ------------------------------------------------------\n");

    // Your animation code here
    char loadingBar[] = "|/-\\";
    int i;
    for (i = 0; i < 30; i++) {
        printf("\r\t\t\t\t\t\t\t\t  Loading... %c", loadingBar[i % 4]);
        fflush(stdout);
        Sleep(100); // Adjust the sleep duration for the desired speed
    }

    printf("\r\t\t\t\t\t\t\t\t\t\t  Loading... Complete!     \n\n\n");
    Sleep(500); // Pause for half a second to let the user see the final message
}

void questionTransitionAnimation() {
	    system("cls");

    printf("\n\n\n\n\t\t\t\t\t\t\t\t  Getting your question ready...\n\n\n\n\n\n\n\n\n\n\n\n\n");
    
    const int animationDuration = 500;  // in milliseconds
    const int numFrames = 20;  // Number of frames in the loading bar
int i;
    for ( i = 0; i < numFrames; ++i) {
    	
        printf("\r\t\t\t\t\t\t\t\t  [");
        int j;
        for ( j = 0; j < numFrames; ++j) {
            if (j <= i) {
            	    customBeep(10000, 2); 
                printf("#");
                
            } else {
                printf(" ");
            }
        }

        printf("] %d%%", (i + 1) * (100 / numFrames));
        fflush(stdout);

        Sleep(animationDuration / numFrames);
    }

    printf("\n");
}



