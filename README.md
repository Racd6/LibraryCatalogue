Library catalogue
public class LibraryCatalogue {
    private String author;
    private String title;
    private String isbn;
    private String subject;
    private String publicationDate;
    
    public LibraryCatalogue(String author, String title, String isbn, String subject, String publicationDate)
    {
        this.author = author;
        this.title = title;
        this.isbn = isbn;
        this.subject = subject;
        this.publicationDate = publicationDate;
    }
    
    public void displayCatalogue() {
        System.out.println("Author: " + author);
        System.out.println("Title: " + title);
        System.out.println("ISBN: " + isbn);
        System.out.println("Subject: " + subject);
        System.out.println("Publication Date: " + publicationDate);
    }
    
    public static void main(String[] args) {
        LibraryCatalogue catalogue = new LibraryCatalogue("Charles Ammi", "Programming", "678907", "How to be a good programmer", "1st March 1986");
        catalogue.displayCatalogue();
    }
}# LibraryCatalogue
