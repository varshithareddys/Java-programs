class LibraryBook
{
    String title;
    String author;
    double price;

    // Static variable
    static int bookCount = 0;

    // Constructor
    LibraryBook(String title, String author, double price)
    {
        this.title = title;
        this.author = author;
        this.price = price;
        bookCount++;
    }

    // Static method
    static void displayBookCount()
    {
        System.out.println("Total Books: " + bookCount);
    }

    // Method to display book details
    void display()
    {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.println("Price: Rs." + price);
        System.out.println();
    }
}

class LibraryDemo
{
    public static void main(String args[])
    {
        LibraryBook b1 = new LibraryBook("Java Programming", "James Gosling", 450);
        LibraryBook b2 = new LibraryBook("Python Basics", "Guido van Rossum", 400);
        LibraryBook b3 = new LibraryBook("C Programming", "Dennis Ritchie", 350);

        b1.display();
        b2.display();
        b3.display();

        // Calling static method
        LibraryBook.displayBookCount();
    }
}
