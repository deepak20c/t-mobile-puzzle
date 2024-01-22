
## Fix Accessibility issues 
    ~ Search icon do not have an accessible name

    ~ fixed the issue Background and foreground colors do not have a sufficient contrast ratio.

    ~ added aria labels in all buttons 

    ~ Dynamic content loaded in aria lables 

    ~ added Alt texts for all the images

## Fix failed Test cases
    fixed the below failed testcases in reading list reducer 
    ~ failedAddToReadingList should undo book addition to the state

    ~ failedRemoveFromReadingList should undo book removal from the state

## Review 
    ~ Removed empty ngOnInit in total-count component 

    ~ Refactored this reducdant 'await' on non- promise from books.controller