# Pagination.README


***PAGING*** - is the act of loading one page of items after another from a database, in order to preserve resources. 


***PAGINATION*** - is a UI element that provides a sequence of page numbers to let the user choose which page to load next.


***PAGE REQUEST IMPLEMENTATION*** - creates a request for the first page with items ordered by the first name and second by the id.

-Whenever we want to load only a slice of a full list of items we can use a **PAGEABLE** instance as an input parameter as it provides the number of the page to load as well as the size of the pages. 

-THE PAGE INDEX IS ZERO-BASED BY DEFAULT !!!!!!!

**PAGING IN A WEB CONTROLLER**


