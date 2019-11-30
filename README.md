#include <stdio.h>
#include <locale.h>

int main()
{
    setlocale(0,"");
    int day = 0x26;
    int month = 0x11;
    int year = 0x2019;
    printf("Мацкив В.А.\n%x.%02x.%x", day, month, year);
    return 0;
}
