#include <stdio.h>

void main() {
    float weight, calories;
    int steps;
    
    // Input
    printf("Enter your weight (in kg): ");
    scanf("%f", &weight);
    printf("Enter the number of steps taken: ");
    scanf("%d", &steps);
    
    // Calculation (using a simplified formula)
    // A common approximation: Calories = Steps * (Weight in kg) * 0.0004
    calories = steps * weight * 0.0004;
    
    // Output
    printf("\n--- Result ---\n");
    printf("For %d steps and weight of %.2f kg:\n", steps, weight);
    printf("Estimated Calories Burned: %.2f kcal\n", calories);
    
    // Ranking based on steps
    if(steps >= 10000) {
        printf("Ranking: Excellent! Keep up the great work!\n");
    }
    else if(steps >= 7000) {
        printf("Ranking: Very Good! You're doing well!\n");
    }
    else if(steps >= 5000) {
        printf("Ranking: Good! Try to reach 7000 steps tomorrow.\n");
    }
    else if(steps >= 3000) {
        printf("Ranking: Average. You need to improve your activity.\n");
    }
    else {
        printf("Ranking: Need to improve significantly. Aim for at least 5000 steps daily.\n");
    }
}
