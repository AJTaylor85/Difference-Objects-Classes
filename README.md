# Difference-Objects-Classes
Week 1 Discussion

The difference between classes and cars is that objects can be multiple parts relating to a class. For example, you could create a book class. 
A class is the main subject that is being broken down. With this class, a book can be broken down into sub-categories called objects. 
These objects would be used to give more detail or information pertaining to the class. With a book, you could make objects for the title, 
author, genre, and even pages. All of these objects represent, as a whole, what is being described (the class). They main difference between 
books and classes is determined by how they are used. Classes are used to group objects together than can possibly even perform tasks. For example,
if there were a microwave class, the objects would be the multiple parts of the microwave. In reality, the microwave is not capable of performing tasks,
however, the door and buttons (objects) would. In this case, the objects can interact with each other to perform the functions of a microwave.



public class Book {
    private String title;
    private String author;
    private int numOfPages;

    Book(String title, String author, int numOfPages) { //This is where the class is identified
        this.title = title;             //these are all objects related to the class
        this.author = author;           //these are all objects related to the class
        this.numOfPages = numOfPages;   //these are all objects related to the class
    }
    public void displayBook() {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.println("Pages: " + numOfPages);
    }

    public static void main(String[] args) {
        Book book1 = new Book("The Alchemist", "Paulo Coelho", 208);
        book1.displayBook();

    }
}
