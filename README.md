# interview2
c
#include <stdio.h>

int main() {
    float CGPA;
    char skill;
    char Name[20];
    
    printf("Name of Candidate:");
    scanf("%s",&Name);
    printf("Enter CGPA of candidate: ");
    scanf("%f", &CGPA);

    printf("Does the candidate have required skills? (y/n): ");
    scanf(" %c", &skill);

    if (CGPA > 7 && skill == 'y') {
        printf("Candidate %s is PASSED in the interview.\n", Name);
    }
    else {
        printf("Candidate %s is NOT PASSED in the interview.\n",Name);
    }

    return 0;
}
