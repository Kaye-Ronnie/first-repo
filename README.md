#include <stdio.h>

void print_chessboard(char (*a)[8]) {
    for (int row = 0; row < 8; row++) {
        for (int col = 0; col < 8; col++) {
            printf("%c ", a[row][col]);
        }
        printf("\n");
    }
}

int main() {
    char chessboard[8][8] = {
        {'r', 'n', 'b', 'q', 'k', 'b', 'n', 'r'},
        {'p', 'p', 'p', 'p', 'p', 'p', 'p', 'p'},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {' ', ' ', ' ', ' ', ' ', ' ', ' ', ' '},
        {'P', 'P', 'P', 'P', 'P', 'P', 'P', 'P'},
        {'R', 'N', 'B', 'Q', 'K', 'B', 'N', 'R'}
    };

    print_chessboard(chessboard);

    return 0;
}
# first-repo
