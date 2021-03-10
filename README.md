#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
int main()
{
int number_of_books = 60;
int Book_cost_per_book = 250;
int shipping_for_the_first_copy = 3;
int shipping_for_the_second_copy = 2;
float total_cost_of_book_for_the_first_copy,total_cost_of_book_for_the_next_copy,total_amount;
total_cost_of_book_for_the_first_copy = (number_of_books)*Book_cost_per_book;
total_cost_of_book_for_the_next_copy = ((number_of_books - 1)*Book_cost_per_book);
total_amount = total_cost_of_book_for_the_first_copy + total_cost_of_book_for_the_next_copy;
printf("the total cost of book to publish : %f", total_amount);
}
