#include<stdio.h>
#include<string.h>
#include<time.h>
#include<stdlib.h>
#include<Windows.h>

struct weapon{
    int damage;
    int durability;
};

struct weapon sword = {60, 110};
struct weapon dagger = {40, 110};
struct weapon spear = {80, 110};
struct weapon weaponUsed;

void mainMenu();
void timer();
void credit();
void pickWeapon();
void usedWeapon();
void dungeon1();
void dungeon2();
void dungeon3();
void attackKecoaTempur();
void attackBigBadLipan();
void attackNyamukWarlord();
void usedWeaponSword();
void usedWeaponDagger();
void usedWeaponSpear();


void mainMenu(){
    printf("\n");
    printf("=======================================================\n");
    printf("===============      Trial by Fire      ===============\n");
    printf("=======================================================\n");
    printf("Start your journey ? ( y (start) / n (main menu) / c (credit) )\n");
    char yn[1];
    scanf("%s",yn);
    if(yn[0] == 'y'){
        pickWeapon();
    }
    if(yn[0] == 'n'){
        mainMenu();
    }
    if(yn[0] == 'c'){
        credit();
    }
}

void timer(){
    int timer = 3;

    while(timer > 0){
        //printf("%d", timer);
        printf("Please wait %d more seconds before attacking\n", timer);
        Sleep(1000);
        timer--;
    }
}

void credit(){
    printf("\n");
    printf("Dev  :    Johanes\n");
    printf("Dev  :    Althaf Rizqi Hariawan\n");
    printf("Dev  :    Mariel Efremia Bimoputri\n");
    printf("Dev  :    Muhamad Dwi Apriyanto\n");
    printf("Dev  :    I Made Prama Sedana\n");
    printf("Dev  :    Cindy Amanda Onggirawan\n");
    printf("Back to Main Menu\n");
    printf(".\n");
    printf(".\n");
    printf(".\n");
    printf(".\n");
    printf(".\n");
    mainMenu();
}


void pickWeapon(){
    printf("\n");
    printf("Choose your desired weapon!\n");
    printf("Greatsword ..... (a)\n");
    printf("Dagger ......... (b)\n");
    printf("Spear .......... (c)\n");
    char weapon[1];
    scanf("%s", weapon);
    if(weapon[0] == 'a'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = sword.damage;
        weaponUsed.durability = sword.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        dungeon1();
    }
    if(weapon[0] == 'b'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = dagger.damage;
        weaponUsed.durability = dagger.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        dungeon1();
    }
    if(weapon[0] == 'c'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = spear.damage;
        weaponUsed.durability = spear.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        dungeon1();
    }
    if(weapon[0] != 'a' && weapon[0] != 'b' && weapon[0] != 'c'){
        pickWeapon();
    }
}

void pickWeaponSec(){
    printf("\n");
    printf("Choose your desired weapon!\n");
    printf("Greatsword ..... (a)\n");
    printf("Dagger ......... (b)\n");
    printf("Spear .......... (c)\n");
    char weapon[1];
    scanf("%s", weapon);
    if(weapon[0] == 'a'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = sword.damage;
        weaponUsed.durability = sword.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
    }
    if(weapon[0] == 'b'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = dagger.damage;
        weaponUsed.durability = dagger.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
    }
    if(weapon[0] == 'c'){
        printf("Good choice....,or is it ?\n");
        weaponUsed.damage = spear.damage;
        weaponUsed.durability = spear.durability;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
    }
    if(weapon[0] != 'a' && weapon[0] != 'b' && weapon[0] != 'c'){
        printf("Some wise old man : Didn't offer you that...\n");
        pickWeaponSec();
    }
}

void dungeon1(){
	printf("\n");
	printf("\n");
	printf("Some wise old man : This is your first trial of all. Win this, and you shall continue your journey.\n");
	printf("\n");
	printf("*A wild Kecoa Tempur has appeared!*\n");
	printf("\n");
	printf("Kecoa Tempur : I shall destroy you right here and right now, for only He is the chosen one\n");
	attackKecoaTempur();
	dungeon2();
}

void dungeon2(){
	printf("\n");
	printf("\n");
	printf("Same wise old man from earlier : This is your second trial of all. Win this, and you shall continue your journey.\n");
	printf("*A wild Kecoa Tempur has appeared, again!*\n");
	printf("*A wild Big Bad Lipan has appeared, again!*\n");
	printf("\n");
	printf("Kecoa Tempur : Hi um.., It's me again. Sorry if it's kinda annoying but um..., now you have to fight two of us.\n");
	printf("Big Bad Lipan : Hiiii, nice to meet you. You look cool, would be sad if you... die...\n");
	printf("Kecoa Tempur : I'll go first\n");
	attackKecoaTempur();
	printf("\n");
	printf("Big Bad Lipan : Slurrpp, ukhukh... just drank some of your health, now fight me!\n");
	attackBigBadLipan();
	printf("Big Bad Lipan : Dayum, that sh*t hurts.You may win this one, but mark my word, you won't go past our Lord'!\n");
	dungeon3();
}

void dungeon3(){
	printf("\n");
	printf("\n");
	printf("Same boring wise old man from earlier : This is your last trial of all. Win this, and you will prove you worth.\n");
	printf("Same boring wise old man from earlier : It is your intention after all.\n");		
	printf("Nyamuk Warlord : Hello, there!\n");
	printf("Nyamuk Warlord : Well, since I am THE lord of this dungeon, I'll have to fight you for formality sake.\n");
	printf("Nyamuk Warlord : But first, you gotta fight Lipan. Kecoa is nowhere to be found though.\n");
	attackBigBadLipan();
	printf("Big Bad Lipan : Fk...(died)\n");
	printf("You : Fk...my weapon broken la\n");
	printf("Same boring wise old man from earlier : Just take new one, dis...\n");
	pickWeaponSec();
	printf("Potion drank, 55 HP added for boss fight.\n");
	attackNyamukWarlord();
	printf("Nyamuk Warlord : Whatever kid, just go, you won I guess...\n");
	printf("\n");
	printf("\n");
	printf("Same boring wise old man from earlier : Well I guess you've won\n");
	printf("Same guy: Congrats :).Now you're stuck here.\n");
	printf("========== THE END ==========\n");
	credit();

}

int potion(int darahPlayer){
	darahPlayer = darahPlayer + 50;
	return darahPlayer;
}

void attackKecoaTempur(){
    // Attack Config
    int darahPlayer = 100;
    int darahKecoa = 100;
    int randomDMG;
    char option[42];


    while(5 > 0){
    printf("Proceed to attack Kecoa Tempur? ( y (yes) / n (no) )\n");
    scanf("%s", &option);
    if(option[0] == 'y'){
        srand(time(0));
        randomDMG = rand() % 60 + 20; //Rework-----------Tergantung Senjata
        printf("\n");
		printf("A successful attack for %d damage!\n", randomDMG);
		printf("Kecoa dealt 10 HP.\n");
        printf("\n");
        timer();
        printf("\n");
    } else if(option[0] == 'n'){
    	printf("\n");
        printf("No place for coward, remember why are you here in the first place\n");
        printf("\n");
        attackKecoaTempur();
    } else {
        printf("\n");
    }


    if(option[0] == 'y'){
        darahKecoa -= randomDMG;
        darahPlayer -= 10;
        weaponUsed.durability -= 10;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        printf("\n");
        printf("Kecoa Tempur's HP = %d\n", darahKecoa);
        printf("Your HP = %d\n", darahPlayer);
        printf("\n");
    }


    if(darahKecoa <= 0){
        printf("Good Job! Kecoa Tempur has been defeated\n");
        break; //----------------------------------------------------------- Back to Main Menu
    } else if(darahPlayer <= 0){
        printf("You lost! shame...");
    }

    }
}

void attackBigBadLipan(){
    // Attack Config
    int darahPlayer = 70;
    int darahLipan = 120;
    int randomDMG;
    char option[42];


    while(5 > 0){
    printf("Proceed to attack Big Bad Lipan? ( y (yes) / n (no) )\n");
    scanf("%s", &option);
    if(option[0] == 'y'){
        srand(time(0));
        randomDMG = rand() % 60 + 20; //Rework-----------Tergantung Senjata
        printf("A successful attack for %d damage!\n", randomDMG);
        printf("Lipan dealt 15 HP.\n");
        printf("\n");
        timer();
        printf("\n");
    } else if(option[0] == 'n'){
        printf("\n");
        printf("No place for coward, remember why are you here in the first place\n");
        printf("\n");
        attackBigBadLipan();
    } else {
        printf("\n");
    }


    if(option[0] == 'y'){
        darahLipan -= randomDMG;
        darahPlayer -= 15;
        weaponUsed.durability -=10;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        printf("\n");
        printf("Big Bad Lipan's HP = %d\n", darahLipan);
        printf("Your HP = %d\n", darahPlayer);
    }


    if(darahLipan <= 0){
        printf("Good Job! Big Bad Lipan has been defeated\n");
        break; //----------------------------------------------------------- Back to Main Menu
    } else if(darahPlayer <= 0){
        printf("lol u ded\n");
    }

    }
}

void attackNyamukWarlord(){
    //Attack Config
    int darahPlayer = 85;
    int darahNyamuk = 130;
    int randomDMG;
    char option[42];


    while(5 > 0){
    printf("Proceed to attack Nyamuk Warlord? ( y (yes) / n (no) )\n");
    scanf("%s", &option);
    if(option[0] == 'y'){
        srand(time(0));
        randomDMG = rand() % 60 + 20;
        printf("A successful attack for %d damage!\n", randomDMG);
        printf("Nyamuk dealt 20 HP.\n");
        printf("\n");
        timer();
        printf("\n");
    }
	if(option[0] == 'n'){
        printf("\n");
        printf("\n");
        attackNyamukWarlord();
    } 


    if(option[0] == 'y'){
        darahNyamuk -= randomDMG;
        darahPlayer -= 20;
        weaponUsed.durability -= 10;
        printf("Current weapon stat :\n");
        printf("Damage     : %d\n", weaponUsed.damage);
        printf("Durability : %d\n", weaponUsed.durability);
        printf("\n");
        printf("Nyamuk Warlord's HP = %d\n", darahNyamuk);
        printf("Your HP = %d\n", darahPlayer);
    }


    if(darahNyamuk <= 0){
        printf("Good Job! Nyamuk Warlord has been defeated\n");
        break; //----------------------------------------------------------- Back to Main Menu
    } else if(darahPlayer <= 0){
        printf("U ded lol");
    }

    }
}

int main(){

    char user[100];
    char yn;

    printf("Insert username : ");
    scanf("%s", user);
    printf("\n");
    printf("Welcome , %s!\n", user);
    mainMenu();
    //startJourney();
    return 0;

}
